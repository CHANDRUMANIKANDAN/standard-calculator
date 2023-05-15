# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
clone the repository and create Djano admin interface

### Step 2:
change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
write Javascript program for implementing five different operations.

### Step 5:
validate the HTML and CSS code
### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
<!DOCTYPE html>
<html>
 <head>
 <title>Calculator in JavaScript</title>
 <style type="text/css">
 table{
 border: 3px solid black;
 margin-left: auto;
 margin-right: auto;
 }
 input[type="text"]{
 border: 2px solid black;
 padding: 20px 40px;
 font-size: 24px;
 font-weight: bold;
 background-color: aqua;
 border-radius: 2px;
 }
 input[type="button"]{
 width: 100%;
 padding: 20px 40px;
 background-color:pink;
 border-radius: 2px;
 }
 </style>
 </head>
 <body bgcolor="violet">
 <form name="form1" onload="result.value=''">
 <h1 style="text-align: center;color:red;">Simple Calculator</h1>
 <h2 style="text-align: center;color:red;"> CHANDRU M
212222100009</h2>
 
 <table id="calc">
 <tr>
 <td colspan="4">
 <input type="text" id="result">
 </td>
 </tr>
 <tr>
 <td><input type="button" value="1" 
onclick="result.value+='1'"/></td>
 <td><input type="button" value="2" 
onclick="result.value+='2'"/></td>
 <td><input type="button" value="3" 
Firefox http://chandrumanikandan.student.saveetha.in:8000/static/html/index.html
2 of 4 5/15/2023, 9:00 AM
OUTPUT:
onclick="result.value+='3'"/></td>
 <td><input type="button" value="+" 
onclick="result.value+='+'"/></td>
 </tr>
 <tr>
 <td><input type="button" value="4" 
onclick="result.value+='4'"/></td>
 <td><input type="button" value="5" 
onclick="result.value+='5'"/></td>
 <td><input type="button" value="6" 
onclick="result.value+='6'"/></td>
 <td><input type="button" value="-" onclick="result.value+='-
'"/></td>
 </tr>
 <tr>
 <td><input type="button" value="7" 
onclick="result.value+='7'"/></td>
 <td><input type="button" value="8" 
onclick="result.value+='8'"/></td>
 <td><input type="button" value="9" 
onclick="result.value+='9'"/></td>
 <td><input type="button" value="*" 
onclick="result.value+='*'"/></td>
 </tr>
 <tr>
 <td><input type="button" value="/" onclick="result.value+='/'"
/></td>
 <td><input type="button" value="0" 
onclick="result.value+='0'"/></td>
 <td><input type="button" value="." 
onclick="result.value+='.'"/></td>
 <td><input type="button" value="=" 
onclick="result.value=eval(result.value)"/></td>
 </tr>
 
 <tr>
 <td colspan="4">
 <input type="button" value="clearall" id="clear" 
onclick="result.value=''">
 </td>
 </tr>
 </table>
 </form>
 </body>
</html>
Firefox http://chandrumanikandan.student.saveetha.in:8000/static/html/index.html


## OUTPUT:
![Screenshot 2023-05-15 090305](https://github.com/CHANDRUMANIKANDAN/standard-calculator/assets/118644502/d7363a41-216b-4ec9-a858-fbd8ad7779b0)

## Result:
The program for designing a simple calculator using Jvascript is created successfully

