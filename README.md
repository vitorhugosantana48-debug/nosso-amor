<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>Para Você ❤️</title>

<style>

body{
background:black;
color:white;
font-family:Arial;
text-align:center;
}

h1{
margin-top:50px;
font-size:40px;
}

img{
width:250px;
border-radius:20px;
margin:10px;
}

button{
padding:15px;
font-size:18px;
border:none;
background:red;
color:white;
border-radius:10px;
cursor:pointer;
}

</style>

</head>

<body>

<h1>Para você ❤️</h1>

<p>
Se você chegou até aqui é porque escaneou meu QR Code.
Eu fiz esse cantinho para lembrar alguns momentos nossos.
</p>

<button onclick="tocarMusica()">Clique aqui</button>

<br><br>

<img src="FOTO1.jpg">
<img src="FOTO2.jpg">
<img src="FOTO3.jpg">

<p>Eu te amo ❤️</p>

<audio id="musica">
<source src="musica.mp3" type="audio/mp3">
</audio>

<script>

function tocarMusica(){
document.getElementById("musica").play();
}

</script>

</body>
</html>
