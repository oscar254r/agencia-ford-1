# agencia-ford-1
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>ford motors</title>
<style>
/* Ejemplo de estilo básico para organizar */
.topnav {
  background-color: hsl(240, 4%, 10%);
  overflow: hidden;
}
.topnav a {
  float: left;
  color: #f3f7f4;
  padding: 14px 16px;
  text-decoration: none;
}
.row {
  display: flex;
}
.row__column {
  flex: 1;
  padding: 10px;
}
.footer {
  text-align: center;
  padding: 10px;
  background-color: #08c9fa;
}
</style>
</head>
<body>

<h1>AGENCIA FORD</h1>
<!-- Crear el menú -->
<div class="topnav">
  <a href="https://www.mined.gob.sv/">INICIO</a>
  <a href="#">MISION</a>
  <a href="#">VISION</a>
  <a href="https://www.nintendo.com/us/">MENDEZESTRADA</a>
</div>

<!-- Cuerpo de la página -->
<div class="row">
  <div class="row__column side">
    <h2>QUÉ CREES TÚ</h2>
    <p>Enrique pensar en nada lo digo con potestad.</p>
  </div>
  <div class="row__column middle">
    <h2>visión</h2>
    <p>Ofrecer vehículos que inspiren confianza y pasión por conducir, integrando diseños y tecnoloia innovadora
  </div>
  <div class="row__column side">
    <h2>Columna 3</h2>
    <p>Y entonces qué hacemos</p>
  </div>
</div>

<!-- Pie de Página -->
<div class="footer">
  <h3>Nacidos Ford, Nacidos Fuertes</h3>
</div>

<div class="footer">
  <source src="lapaz.mp3" type="audio/mp3">

  <h3>nacidos para la velocidad</h3>
</div>

<div class="footer">
  <h3>YO NO PUEDO TU MUNDO, EL MIO Y EL DE OTROS</h3>
</div>

<!-- Audio -->
<audio controls>
  <source src="tokio drif.aac" type="audio/mp3">
  Tu navegador no soporta audio HTML5.
</audio>

<!-- Imágenes en movimiento -->
<marquee>
  <img src="images/descarga 2.avif" width="400" height="200" alt="Imagen en movimiento">
</marquee>

<marquee behavior="alternate">
  <img src="Images/descarga.jpg" width="400" height="200"
       onmouseover="this.src='nip2.jpg'"
       onmouseout="this.src='Cari2.png'"
       alt="Imagen alternativa">
</marquee>

<!-- Video -->
<video width="600" height="400" controls>
  <source src="The All-New 2024 Ford Mustang®️_ A Wake-Up Call _ Ford (1).mp4" type="video/mp4">
</video>
     
<!-- Enlaces finales -->
<p><a href="Base Access China.html">Registros</a></p>
<p><a href="index.html">A hoja 2</a></p>
<p><a href="iindex.htm">A hoja 3</a></p>

</body>
</html>
