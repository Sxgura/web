<!DOCTYPE html><html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>By Sxgura Inc.</title><style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#000;
color:#fff;
display:flex;
justify-content:center;
align-items:center;
min-height:100vh;
padding:20px;
overflow:hidden;
}

.card{
width:100%;
max-width:750px;
padding:35px;
border:1px solid rgba(25,118,255,.25);
border-radius:25px;
background:#050505;
text-align:center;
box-shadow:0 0 40px rgba(25,118,255,.15);
}

.logo{
width:130px;
height:130px;
border-radius:24px;
object-fit:cover;
border:2px solid #1976ff;
margin-bottom:20px;
}

h1{
font-size:34px;
color:#1976ff;
margin-bottom:10px;
}

.subtitle{
color:#9ca3af;
font-size:15px;
margin-bottom:25px;
}

.typing{
height:90px;
display:flex;
justify-content:center;
align-items:center;
font-size:24px;
font-weight:700;
color:#1976ff;
text-align:center;
padding:0 10px;
}

.info{
margin-top:25px;
color:#d5d5d5;
line-height:1.9;
font-size:16px;
}

.buttons{
margin-top:35px;
display:flex;
justify-content:center;
gap:15px;
flex-wrap:wrap;
}

.btn{
padding:14px 30px;
background:#1976ff;
color:#fff;
text-decoration:none;
border-radius:14px;
font-weight:700;
transition:.3s;
}

.btn:hover{
transform:translateY(-3px);
box-shadow:0 0 25px rgba(25,118,255,.5);
}

.footer{
margin-top:30px;
font-size:14px;
color:#666;
}

@media(max-width:600px){

h1{
font-size:28px;
}

.typing{
font-size:20px;
height:100px;
}

.info{
font-size:15px;
}

}

</style></head><body><div class="card"><img
src="https://i.ibb.co/Kpqhqg1W/file-000000004e1c720e9e07fa81e9083a95.png"
class="logo"
alt="Logo"

«»

<h1>By Sxgura Inc.</h1><div class="subtitle">
Proyecto en constante evolución
</div><div id="typing" class="typing"></div><div class="info">🎮 Juegos interactivos y entretenimiento

<br><br>

📥 Sistema avanzado de descargas

<br><br>

🛠 Herramientas y funciones útiles

<br><br>

⚡ Nuevas características en desarrollo

<br><br>

🔄 Actualizaciones frecuentes

<br><br>

🚀 Proyecto mantenido y mejorado constantemente

</div><div class="buttons"><a
href="https://wa.me/254102300454"
target="_blank"
class="btn">
WhatsApp
</a>

<a
href="https://t.me/EllSxgura"
target="_blank"
class="btn">
Telegram
</a>

</div><div class="footer">
© By Sxgura Inc. • Todos los derechos reservados
</div></div><script>

const textos = [

"Bienvenido a By Sxgura Inc.",

"Juegos y entretenimiento",

"Sistema avanzado de descargas",

"Herramientas y funciones útiles",

"Actualizaciones constantes",

"Nuevas características en desarrollo",

"Proyecto en constante evolución",

"Mejorando cada versión",

"Gracias por visitarnos"

];

let indice = 0;
let letra = 0;
let escribiendo = true;

const typing = document.getElementById("typing");

function animar(){

const texto = textos[indice];

if(escribiendo){

typing.textContent =
texto.substring(0, letra++);

if(letra > texto.length){

escribiendo = false;

setTimeout(animar, 2500);

return;

}

}else{

typing.textContent =
texto.substring(0, letra--);

if(letra === 0){

escribiendo = true;

indice++;

if(indice >= textos.length){

indice = 0;

}

}

}

setTimeout(animar, 70);

}

animar();

</script></body>
</html>
