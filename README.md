<!DOCTYPE html>
<html lang= en >
chead>
‹link rel="stylesheet" href-"https://pyscript.net/latest/pyscript.css"/>
<script defer src="https://pyscript.net/latest/pyscript.js"></script>
<style>
labelf
display:block;
</stvle>
</head>
<body>
<torm>
«label for-"operandOne">X: </label> <input name="operandOne" id= "operandOne" value="10">
<label for="total">Result:</label><div name="total" id= "total"></div>
</form>
<py-script>
input box
= Element ("operandone")
operandOne
= float (input box.value)
result = Element ("total")
result.write("Hello!
The input says:" + str(operandone))
</py-script>
</body>
</html>
