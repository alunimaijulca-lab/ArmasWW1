# ArmasWW1
Trabajo informatica
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Armas de la Primera Guerra Mundial</title>
<link rel="stylesheet" href="style.css">
<style>
  body{
    font-family: Arial;
    margin:0;
    background-color:#f4eaea;
}

header{
    background-color:#800020; /* rojo vino */
    color:white;
    text-align:center;
    padding:20px;
}

nav{
    background-color:#5c0f0f; /* rojo vino oscuro */
    text-align:center;
    padding:10px;
}

nav a{
    color:white;
    margin:10px;
    text-decoration:none;
    font-weight:bold;
}

nav a:hover{
    color:#ffd6d6;
}

.contenido{
    padding:20px;
}

img{
    width:400px;
    margin-top:10px;
}

table{
    border-collapse:collapse;
    width:80%;
    margin-top:20px;
}

table, th, td{
    border:1px solid #800020;
}

th{
    background-color:#800020;
    color:white;
}

th, td{
    padding:10px;
    text-align:center;
}

.boton-enlace {
  text-align: center;
  margin: 20px 0;
}

.boton-enlace a button {
  background-color: #800020;
  color: white;
  border: none;
  padding: 12px 25px;
  font-size: 16px;
  border-radius: 8px;
  cursor: pointer;
  transition: background-color 0.3s, transform 0.2s;
}

.boton-enlace a button:hover {
  background-color: #5a0015; 
  transform: scale(1.05);
}

footer{
    background-color:#800020;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:30px;
}
</style>
</head>

<body>

<header>
<h1>Armas WW1</h1>

<nav>
<a href="#introduccion">Descripcion</a>
<a href="#imagen">Imagen</a>
<a href="#video">Video</a>
<a href="#tabla">Tabla de armas</a>
</nav>

</header>

<div class="contenido">

<h2 id="introduccion">Descripcion</h2>

<p>
La Primera Guerra Mundial, introdujo muchas armas modernas que cambiaron la forma de combatir. Se introdujeron armas automaticas y semiautomaticas.
</p>

<hr>

<h2 id="imagen">Imagen</h2>

<img src="https://i.pinimg.com/736x/bd/41/ea/bd41ea70ba6ee86ff0cb19deca1acf52.jpg" alt="Armas WW1">

<h2 id="video">Video explicativo</h2>

<iframe width="560" height="315" src="https://www.youtube.com/embed/UVV14_VeKEA?si=6t7Pm5FR-S06kHOu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h3 id="tabla">Tabla de armas</h3>

<table border="1">
<tr>
<th>Arma</th>
<th>País</th>
<th>Año</th>
<th>Tipo</th>
</tr>

<tr>
<td>Maxim Machine Gun</td>
<td>Reino Unido</td>
<td>1884</td>
<td>Ametralladora</td>
</tr>

<tr>
<td>Lee-Enfield</td>
<td>Reino Unido</td>
<td>1895</td>
<td>Rifle</td>
</tr>

<tr>
<td>Luger P08</td>
<td>Alemania</td>
<td>1908</td>
<td>Pistola</td>
</tr>
</table>

<!-- Botón moderno rojo vino -->
<div class="boton-enlace">
  <a href="https://granadasww1.netlify.app/" target="_blank">
    <button>Ir a la pagina de las granadas</button>
  </a>
</div>

</div>

<footer>
<p>Trabajo de informatica</p>
</footer>

</body>
</html>
