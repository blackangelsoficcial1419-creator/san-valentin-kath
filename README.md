<!DOCTYPE html>
<html>
<head>
<title>¿Quieres ser mi San Valentín?</title>
<style>
body{
  text-align:center;
  font-family:sans-serif;
  background:#ffccd5;
  margin-top:100px;
}
button{
  padding:10px 20px;
  font-size:18px;
  margin:10px;
  border:none;
  border-radius:10px;
  cursor:pointer;
}
#no{
  position:absolute;
}
</style>
</head>
<body>

<h1>¿Quieres ser mi San Valentín? 💖</h1>
<button onclick="aceptar()">Sí ❤️</button>
<button id="no" onmouseover="mover()">No 😢</button>

<script>
function aceptar(){
  alert("Sabía que dirías que sí 😍💘");
}
function mover(){
  let btn = document.getElementById("no");
  btn.style.top = Math.random()*400 + "px";
  btn.style.left = Math.random()*400 + "px";
}
</script>

</body>
</html>
