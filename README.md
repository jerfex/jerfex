<!DOCTYPE html>
<html>
<head>
	<title>Formatador de código Java</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.2.0/styles/default.min.css">
	<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.2.0/highlight.min.js"></script>
	<script>hljs.highlightAll();</script>
	<style>
		pre.language-java {
			font-family: Consolas, monospace;
			font-size: 16px;
			color: #333;
			background-color: #f7f7f7;
			padding: 10px;
			border-radius: 5px;
			overflow-x: auto;
		}
	</style>
</head>
<body>
	<h1>Formatador de código Java</h1>

	<p>Insira o código Java abaixo:</p>

	<textarea id="codigo" rows="10" cols="50"></textarea>

	<button onclick="formatar()">Formatar</button>

	<br><br>

	<h2>Resultado:</h2>

	<pre id="resultado" class="language-java"></pre>

	<script>
		function formatar() {
			var codigo = document.getElementById("codigo").value;
			document.getElementById("resultado").innerHTML = codigo;
			hljs.highlightAll();
		}
	</script>
</body>
</html>
