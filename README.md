# Design of a Standard Calculator
## AIM:
To design a web application for a standard calculator.

## DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for creating attractive colors.

## Step 4:
Write JavaScript program for implementing five different operations.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
    <head>
        <title>SEC Demo on Calculator</title>
        <style type="text/css">
        table{
            border: 3px 
            solid turquoise;
            margin-left: auto;
            margin-right: auto;
            
        }
        input[type="text"]{
            border: 2px solid black;
            padding: 20px 40px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            border:2px solid black;
            width: 100%;
            padding: 20px 40px;
            background-color:rgb(255, 65, 245);
            border-radius: 2px;
        }
        </style>
    </head>
    <body style="background-color:#000c18">
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:rgb(255, 65, 245);">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
                <td><input type="button" value="*" onclick="result.value+=''"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="clear all" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```
## Server Output:
![sop](https://github.com/JAYAVARTHAN-P/calc/assets/121369281/3469c076-1340-4f31-b974-85e0ab20e07f)


## Client Output:

![cop](https://github.com/JAYAVARTHAN-P/calc/assets/121369281/0286a54f-d6c7-410f-96c0-54408889ce8a)
