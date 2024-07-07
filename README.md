### index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Scientific Calculator</title>
    <style>
        body {
            background-color: #f4f4f9;
            font-family: Arial, sans-serif;
        }

        h1 {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }

        .formstyle {
            width: 350px;
            margin: 50px auto;
            border: 3px solid #0f0b0b;
            border-radius: 10px;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        #calc {
            width: calc(100% - 20px);
            border: 2px solid #333;
            border-radius: 5px;
            padding: 15px;
            margin: 10px 0;
            font-size: 20px;
            text-align: right;
            background-color: #f0f0f0;
        }

        input[type="button"] {
            width: 60px;
            height: 60px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            margin: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        input[type="button"]:hover {
            background-color: #b30098;
        }

        #clear {
            width: calc(100% - 20px);
            background-color: #dc3545;
            color: white;
            border: none;
            border-radius: 5px;
            padding: 15px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 10px;
        }

        #clear:hover {
            background-color: #c82333;
        }
    </style>
</head>
<body>
    <h1>Scientific Calculator</h1>
    <div class="formstyle">
        <form name="form1">
            <input id="calc" type="text" name="answer"><br><br>
            <input type="button" value="AC" onclick="form1.answer.value = ''">
            <input type="button" value="DEL" onclick="form1.answer.value = form1.answer.value.slice(0, -1)">
            <input type="button" value="%" onclick="form1.answer.value += '%'">
            <input type="button" value="." onclick="form1.answer.value += '.'"><br><br>
            <input type="button" value="1" onclick="form1.answer.value += '1'">
            <input type="button" value="2" onclick="form1.answer.value += '2'">
            <input type="button" value="3" onclick="form1.answer.value += '3'">
            <input type="button" value="+" onclick="form1.answer.value += '+'"><br><br>
            <input type="button" value="4" onclick="form1.answer.value += '4'">
            <input type="button" value="5" onclick="form1.answer.value += '5'">
            <input type="button" value="6" onclick="form1.answer.value += '6'">
            <input type="button" value="-" onclick="form1.answer.value += '-'"><br><br>
            <input type="button" value="7" onclick="form1.answer.value += '7'">
            <input type="button" value="8" onclick="form1.answer.value += '8'">
            <input type="button" value="9" onclick="form1.answer.value += '9'">
            <input type="button" value="*" onclick="form1.answer.value += '*'"><br><br>
            <input type="button" value="/" onclick="form1.answer.value += '/'">
            <input type="button" value="0" onclick="form1.answer.value += '0'">
            <input type="button" value="." onclick="form1.answer.value += '.'">
            <input type="button" value="=" onclick="form1.answer.value = eval(form1.answer.value)"><br><br>
            <input type="button" value="Clear All" onclick="form1.answer.value = ''" id="clear">
        </form>
    </div>
</body>
</html>
```

### style.css

```
<style>
 h1 {
      text-align: center;
      padding: 23px;
      background-color: skyblue;
      color: white;
    }


#clear{
width: 270px;
border: 3px solid gray;
	border-radius: 3px;
	padding: 20px;
	background-color: red;
    
}

.formstyle
{
width: 300px;
height: 530px;
margin: auto;
border: 3px solid skyblue;
border-radius: 5px;
padding: 20px;
}


input
{
width: 20px;
background-color: green;
color: white;
border: 3px solid gray;
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

```

### output:
![Screenshot (57)](https://github.com/devanandan07/calculator-mern/assets/145025017/87cc8383-25cd-48f6-a377-2bbc16f4c1d0)
