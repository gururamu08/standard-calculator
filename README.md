### Design of a Standard Calculator
### AIM:

To design a web application for a standard calculator.
### DESIGN STEPS:
### Step 1:

Fork and clone the repository,then we want to create a project and app using django framework.
### Step 2:

Create the templates folder follows with app folder in that app folder we want to create a required html files.
### Step 3:

Change the settings.py,views.py,urls.py.
### Step 4:

Write a revalent code in that html file.
### Step 5:

Validate the HTML and CSS code.
### Step 6:

Publish the website in the given URL.


### PROGRAM :
```
### DEVELOPED BY : GURUMOORTHI R
REGISTER NUMBER : 22008475

<!DOCTYPE html>
<html>
    <head>
        <title>SEC Demo on Calculator</title>
        <style type="text/css">
        table{
            border: 10px solid rgb(17, 16, 16);
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid rgb(15, 13, 15);
            padding: 20px 30px;
            font-size: 32px;
            font-weight: bold;
            border-radius: 10px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 20px;
            background-color:rgb(112, 231, 227);
            border-radius: 25px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:blue;">Simple Calculator</h1>
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
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
                
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
                
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="clearall" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>

```

## OUTPUT:
![OUTPUT](/Screenshot%202023-01-27%20181449.jpg)

## Result:
The output for calculator is displayed successfully

