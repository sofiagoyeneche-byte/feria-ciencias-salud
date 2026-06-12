# feria-ciencias-salud
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Salud Digestiva y Salud Mental</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f4fbff;
color:#333;
overflow-x:hidden;
}

header{
height:100vh;
background:linear-gradient(135deg,#4CAF50,#2196F3);
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
color:white;
padding:20px;
}

header h1{
font-size:4rem;
margin-bottom:20px;
animation:aparecer 2s;
}

header p{
font-size:1.4rem;
max-width:800px;
animation:aparecer 3s;
}

@keyframes aparecer{
from{
opacity:0;
transform:translateY(50px);
}
to{
opacity:1;
transform:translateY(0);
}
}

nav{
position:sticky;
top:0;
background:white;
padding:15px;
box-shadow:0 2px 10px rgba(0,0,0,.2);
z-index:100;
}

nav ul{
display:flex;
justify-content:center;
gap:20px;
list-style:none;
flex-wrap:wrap;
}

nav a{
text-decoration:none;
color:#2196F3;
font-weight:bold;
}

section{
padding:80px 10%;
}

h2{
text-align:center;
margin-bottom:40px;
font-size:2.5rem;
color:#2196F3;
}

.tarjetas{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.tarjeta{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.15);
transition:.4s;
}

.tarjeta:hover{
transform:translateY(-10px);
}

.icono{
font-size:60px;
text-align:center;
margin-bottom:15px;
}

.dibujo{
display:flex;
justify-content:center;
align-items:center;
gap:30px;
flex-wrap:wrap;
font-size:90px;
margin-top:30px;
}

.flecha{
font-size:60px;
color:#ff9800;
}

.estadistica{
background:white;
padding:30px;
border-radius:20px;
margin-top:20px;
box-shadow:0 5px 15px rgba(0,0,0,.15);
}

.barra{
height:35px;
background:#ddd;
border-radius:20px;
overflow:hidden;
margin-top:10px;
}

.relleno{
height:100%;
background:linear-gradient(90deg,#4CAF50,#2196F3);
width:80%;
animation:cargar 3s;
}

@keyframes cargar{
from{
width:0;
}
to{
width:80%;
}
}

.consejos{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.consejo{
background:#fff;
padding:20px;
border-radius:15px;
box-shadow:0 4px 10px rgba(0,0,0,.15);
}

footer{
background:#2196F3;
color:white;
text-align:center;
padding:40px;
}

.boton{
display:inline-block;
margin-top:30px;
padding:15px 30px;
background:#4CAF50;
color:white;
text-decoration:none;
border-radius:10px;
font-size:1.1rem;
transition:.3s;
}

.boton:hover{
background:#2e7d32;
}

</style>
</head>
<body>

<header>

<h1>🧠❤️🍎</h1>

<h1>Salud Digestiva y Salud Mental</h1>

<p>
"Cuidar tu salud digestiva es también cuidar tu salud mental y protegerte de las adicciones tecnológicas"
</p>

<a href="#conexion" class="boton">Comenzar</a>

</header>

<nav>
<ul>
<li><a href="#conexion">Conexión</a></li>
<li><a href="#vago">Nervio Vago</a></li>
<li><a href="#adicciones">Tecnología</a></li>
<li><a href="#consejos">Consejos</a></li>
</ul>
</nav>

<section id="conexion">

<h2>🧠 Conexión Intestino - Cerebro</h2>

<div class="dibujo">

🍎

<div class="flecha">⚡</div>

🧠

</div>

<br>

<p style="text-align:center;font-size:1.2rem;">
El intestino y el cerebro están conectados constantemente.
Las emociones afectan la digestión y la salud digestiva influye en nuestro estado de ánimo.
</p>

</section>

<section id="vago">

<h2>⚡ El Nervio Vago</h2>

<div class="tarjetas">

<div class="tarjeta">
<div class="icono">⚡</div>
<h3>Comunicación</h3>
<p>
Transporta información entre el intestino y el cerebro.
</p>
</div>

<div class="tarjeta">
<div class="icono">😟</div>
<h3>Estrés</h3>
<p>
El estrés puede alterar el funcionamiento digestivo.
</p>
</div>

<div class="tarjeta">
<div class="icono">😊</div>
<h3>Bienestar</h3>
<p>
Hábitos saludables favorecen una mejor comunicación.
</p>
</div>

</div>

</section>

<section id="adicciones">

<h2>📱 Adicciones Tecnológicas</h2>

<div class="tarjetas">

<div class="tarjeta">
<div class="icono">📱</div>
<h3>Uso excesivo</h3>
<p>
Muchas horas frente a pantallas pueden afectar el sueño y la concentración.
</p>
</div>

<div class="tarjeta">
<div class="icono">🎮</div>
<h3>Búsqueda de recompensas</h3>
<p>
Las aplicaciones están diseñadas para captar nuestra atención constantemente.
</p>
</div>

<div class="tarjeta">
<div class="icono">😴</div>
<h3>Consecuencias</h3>
<p>
Ansiedad, estrés, cansancio y dificultades para desconectarse.
</p>
</div>

</div>

<div class="estadistica">

<h3>Ejemplo de impacto del exceso de pantallas</h3>

<div class="barra">
<div class="relleno"></div>
</div>

<p style="margin-top:15px;">
Más tiempo frente a pantallas suele relacionarse con mayores niveles de estrés y menor calidad de sueño.
</p>

</div>

</section>

<section id="consejos">

<h2>🌱 ¿Cómo cuidarnos?</h2>

<div class="consejos">

<div class="consejo">
🥗 Comer frutas y verduras.
</div>

<div class="consejo">
💧 Tomar suficiente agua.
</div>

<div class="consejo">
🏃 Realizar actividad física.
</div>

<div class="consejo">
😴 Dormir entre 8 y 10 horas.
</div>

<div class="consejo">
📵 Reducir el tiempo de pantalla.
</div>

<div class="consejo">
👨‍👩‍👧 Compartir tiempo con familia y amigos.
</div>

</div>

</section>

<section>

<h2>🎯 Conclusión</h2>

<p style="text-align:center;font-size:1.3rem;max-width:900px;margin:auto;">
Nuestro intestino y nuestro cerebro trabajan en equipo.
Mantener hábitos saludables ayuda a cuidar la salud física, emocional y a prevenir conductas adictivas relacionadas con la tecnología.
</p>

</section>

<footer>

<h2>🔬 Feria de Ciencias</h2>

<p>
Proyecto: Salud Digestiva, Salud Mental y Prevención de las Adicciones Tecnológicas
</p>

<br>

<p>
Realizado por estudiantes de secundaria.
</p>

</footer>

</body>
</html>