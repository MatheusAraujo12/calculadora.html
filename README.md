# calculadora.html

<!DOCTYPE html>
<html>
<head>
	<title>Calculadora</title>
</head>
<body>
	<h1> Minha Calculadora </h1>

Primeiro número </br>
<input id= "n1" type="number"/><br> </br>
Segundo número </br>
<input id= "n2" type= "number"/></br> </br>

<button onclick="somar">Somar</button>
<Button onclick="subtrair">Subtrair</Button>
<button onclick="multiplicar">Multiplicar</button>
<button onclick="dividir">Dividir</button>

O resultado é <span></span>

<script>
	var n1 = document.querySelector("#n1")
	var n2 = document.querySelector("#n2")
	var resultado = document.querySelector("span")

	function somar() {
		resultado.innerHTML = parseInt(n1.value)+(parseInt(n2.value)
	}
