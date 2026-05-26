
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Evercito</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background: linear-gradient(135deg,#0f172a,#1e293b,#334155);
    color:white;
}

/* HEADER */

header{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    flex-direction:column;
    background-image:url('https://images.unsplash.com/photo-1515879218367-8466d910aaa4');
    background-size:cover;
    background-position:center;
    position:relative;
}

header::before{
    content:"";
    position:absolute;
    width:100%;
    height:100%;
    background:rgba(0,0,0,0.7);
}

.header-content{
    position:relative;
    z-index:1;
}

header h1{
    font-size:70px;
    color:#38bdf8;
    margin-bottom:20px;
}

header p{
    font-size:22px;
    width:70%;
    margin:auto;
    line-height:1.6;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#38bdf8;
    color:white;
    text-decoration:none;
    border-radius:10px;
    transition:0.3s;
    font-weight:bold;
}

.btn:hover{
    background:#0ea5e9;
    transform:scale(1.05);
}

/* TECNOLOGIAS */

.section{
    padding:80px 10%;
}

.section h2{
    text-align:center;
    font-size:45px;
    margin-bottom:50px;
    color:#38bdf8;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#1e293b;
    padding:30px;
    border-radius:20px;
    transition:0.4s;
    text-align:center;
    box-shadow:0 0 20px rgba(0,0,0,0.5);
}

.card:hover{
    transform:translateY(-10px);
    background:#334155;
}

.card img{
    width:80px;
    margin-bottom:20px;
}

.card h3{
    margin-bottom:15px;
    color:#38bdf8;
}

.card p{
    line-height:1.6;
}

/* FOOTER */

footer{
    text-align:center;
    padding:30px;
    background:#020617;
    margin-top:40px;
}

footer p{
    color:#94a3b8;
}

</style>
</head>
<body>

<header>

<div class="header-content">

<h1>🚀 Evercito</h1>

<p>
Proyecto educativo enfocado en el aprendizaje y desarrollo
de software utilizando tecnologías modernas de programación,
bases de datos y diseño web.
</p>

<a href="#" class="btn">Explorar Proyecto</a>

</div>

</header>

<section class="section">

<h2>🌐 Tecnologías Utilizadas</h2>

<div class="cards">

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/732/732212.png">
<h3>HTML5</h3>
<p>
Lenguaje utilizado para crear la estructura de páginas web.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/732/732190.png">
<h3>CSS3</h3>
<p>
Permite agregar estilos, colores y diseños modernos.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png">
<h3>JavaScript</h3>
<p>
Agrega interactividad y funcionalidades dinámicas.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/226/226777.png">
<h3>Java</h3>
<p>
Lenguaje robusto utilizado para aplicaciones y sistemas.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/2772/2772128.png">
<h3>SQL</h3>
<p>
Permite gestionar y manipular bases de datos.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968332.png">
<h3>PHP</h3>
<p>
Desarrollo web dinámico y conexión con servidores.
</p>
</div>

<div class="card">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png">
<h3>Python</h3>
<p>
Lenguaje potente utilizado en IA, automatización y desarrollo.
</p>
</div>

</div>

</section>

<section class="section">

<h2>🎯 Objetivos del Proyecto</h2>

<div class="cards">

<div class="card">
<h3>📚 Aprendizaje</h3>
<p>
Mejorar habilidades de programación y desarrollo web.
</p>
</div>

<div class="card">
<h3>💻 Frontend</h3>
<p>
Practicar diseño moderno e interfaces responsivas.
</p>
</div>

<div class="card">
<h3>🗄️ Backend</h3>
<p>
Comprender lógica del sistema y bases de datos.
</p>
</div>

</div>

</section>

<footer>

<p>
⭐ Gracias por visitar Evercito — Antonio Mendez
</p>

</footer>

</body>
</html>
