# Ex.08 Design of a Standard Calculator
## Date:20.12.23

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
 ```
<!-- Create a simple Program to build the Calculator in JavaScript using with HTML and CSS web languages. -->  
<!DOCTYPE html>  
<html lang = "en">  
<head>  
<title> JavaScript Calculator </title>  
  
<style>  
h1 {  
    text-align: center;  
    padding: 23px;  
    background-color: rgb(232, 239, 29);  
    color: rgb(62, 17, 225);  
    }  
  
h2 {  
    text-align: center;  
    padding: 23px;  
    background-color: rgb(220, 239, 55);  
    color: rgb(54, 17, 221);  
    }  
#clear{  
    width: 270px;  
    border: 3px solid rgb(15, 14, 14);  
    border-radius: 3px;  
    padding: 20px;  
    background-color: rgb(242, 30, 217);  
}  
 
.formstyle  
{  
width: 300px;  
height: 530px;  
margin: auto;  
border: 3px solid rgb(22, 24, 24);  
border-radius: 5px;  
padding: 20px;  
}  
  
  
  
input  
{  
width: 20px;  
background-color: rgb(30, 223, 223);  
color: rgb(32, 31, 31);  
border: 3px solid rgb(25, 24, 26);  
    border-radius: 5px;  
    padding: 26px;  
    margin: 5px;  
    font-size: 15px;  
}  
  
  
#calc{  
width: 250px;  
border: 5px solid black;  
    border-radius: 3px;  
    padding: 20px;  
    margin: auto;  
}  
  
</style>  
  
</head>  
<body>  
<h1> JANANI S 23013409 </h1> 
<h2> SIMPLE CALCULATOR </h2> 
<div class= "formstyle">  
<form name = "form1">  
      
    

    <!-- This input box shows the button pressed by the user in calculator. -->  
  <input id = "calc" type ="text" name = "answer"> <br> <br>  
  <!-- Display the calculator button on the screen. -->  
  <!-- onclick() function display the number prsses by the user. -->  
  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">  
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">  
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">  
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">  
  <br> <br>  
    
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">  
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">  
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">  
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">  
  <br> <br>  
    
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">  
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">  
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">  
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">  
  <br> <br>  
    
    
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">  
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">  
    <input type = "button" value = "%" onclick = "form1.answer.value += '%' ">  
    <!-- When we click on the '=' button, the onclick() shows the sum results on the calculator screen. -->  
  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">  
  <br>   
  <!-- Display the Cancel button and erase all data entered by the user. -->  
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >  
  <br>   
    
</form>  
</div>  
</body>  
</html>

 ```

## OUTPUT:
![Alt text](<Janani/calcapp/static/Screenshot (64).png>)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
