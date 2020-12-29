# Calculadora-php-basica

index.php



<!DOCTYPE html>
//MANUEL ARGILER CODE
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calcular MUCHO</title>
</head>
<body>

    <form action="pagina2.php" method="POST">
    <input type="text" name="caja1" id="caja1">
    <select name="operacion" id="">
        <option value="+">+</option>
        <option value="-">-</option>
        <option value="*">*</option>
        <option value="/">/</option>
    </select>

    <input type="text" name="caja2" id="caja2">

    </form>
    
</body>
</html>










pagina2.php 


<?php
//MANUELA
$num1 = $_POST['caja1']
$num2 = $_POST['caja2']
$operacion = $_POST['operacion']
$resultado =0;


if(operacion == "+"){

    $resultado = $num1 + $num2;
} else if(operacion == "-"){
    $resultado = $num1- $num2;
}
else if(operacion == "*"){
    $resultado = $num1 * $num2;
}
else if(operacion == "/"){
    $resultado = $num1 / $num2;
}
echo "El resultado es:" .$resultado;

?>





