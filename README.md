
<div align="center">

<img src="https://cdn-icons-png.flaticon.com/512/1055/1055687.png" width="180">

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Evercito</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    height:100vh;
    overflow:hidden;
    background: linear-gradient(135deg,#020617,#0f172a,#1e293b);
    display:flex;
    justify-content:center;
    align-items:center;
    position:relative;
}

/* Fondo animado */
body::before{
    content:"";
    position:absolute;
    width:200%;
    height:200%;
    background:
    radial-gradient(circle,#38bdf8 2px, transparent 2px),
    radial-gradient(circle,#9333ea 2px, transparent 2px),
    radial-gradient(circle,#22c55e 2px, transparent 2px);
    background-size:120px 120px;
    animation:mover 15s linear infinite;
    opacity:0.3;
}

@keyframes mover{
    0%{
        transform:translate(0,0);
    }
    100%{
        transform:translate(-120px,-120px);
    }
}

/* Contenedor */
.container{
    position:relative;
    z-index:10;
    text-align:center;
    padding:50px;
    border-radius:25px;
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(10px);
    box-shadow:
    0 0 20px #38bdf8,
    0 0 40px #9333ea,
    0 0 60px #22c55e;
    animation:flotar 3s ease-in-out infinite;
}

@keyframes flotar{
    0%,100%{
        transform:translateY(0px);
    }
    50%{
        transform:translateY(-10px);
    }
}

/* Titulo */
h1{
    font-size:65px;
    color:white;
    text-transform:uppercase;
    letter-spacing:4px;
    text-shadow:
    0 0 10px #38bdf8,
    0 0 20px #38bdf8,
    0 0 40px #9333ea,
    0 0 60px #22c55e;
    animation:brillo 2s infinite alternate;
}

@keyframes brillo{
    from{
        filter:brightness(1);
    }
    to{
        filter:brightness(1.5);
    }
}

/* Texto */
p{
    margin-top:20px;
    color:#e2e8f0;
    font-size:20px;
    letter-spacing:1px;
}

/* Boton */
button{
    margin-top:30px;
    padding:15px 40px;
    border:none;
    border-radius:50px;
    background:linear-gradient(45deg,#38bdf8,#9333ea,#22c55e);
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:0.4s;
    box-shadow:0 0 20px #38bdf8;
}

button:hover{
    transform:scale(1.1);
    box-shadow:
    0 0 20px #38bdf8,
    0 0 40px #9333ea,
    0 0 60px #22c55e;
}

/* Luces flotantes */
.luz{
    position:absolute;
    border-radius:50%;
    filter:blur(15px);
    animation:subir 10s linear infinite;
}

.luz:nth-child(1){
    width:120px;
    height:120px;
    background:#38bdf8;
    left:10%;
    animation-duration:8s;
}

.luz:nth-child(2){
    width:150px;
    height:150px;
    background:#9333ea;
    right:10%;
    animation-duration:12s;
}

.luz:nth-child(3){
    width:100px;
    height:100px;
    background:#22c55e;
    bottom:10%;
    animation-duration:10s;
}

@keyframes subir{
    0%{
        transform:translateY(0px);
        opacity:0.5;
    }
    50%{
        opacity:1;
    }
    100%{
        transform:translateY(-80px);
        opacity:0.5;
    }
}

</style>
</head>

<body>

<div class="luz"></div>
<div class="luz"></div>
<div class="luz"></div>

<div class="container">
    <h1>🚀 Bienvenidos <br> les saluda Evercito</h1>
    
    <p>
        Desarrollo • Diseño • Creatividad • Tecnología
    </p>

    <button>Entrar Ahora</button>
</div>

</body>
</html>

### 💻 Proyecto de Desarrollo Web y Programación

<img src="https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5">
<img src="https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3">
<img src="https://img.shields.io/badge/JavaScript-yellow?style=for-the-badge&logo=javascript">
<img src="https://img.shields.io/badge/Java-red?style=for-the-badge&logo=java">
<img src="https://img.shields.io/badge/Python-darkblue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/PHP-purple?style=for-the-badge&logo=php">
<img src="https://img.shields.io/badge/SQL-black?style=for-the-badge&logo=mysql">

---

<img src="https://images.unsplash.com/photo-1515879218367-8466d910aaa4?auto=format&fit=crop&w=1200&q=80" width="100%">

</div>

---

# 📖 Descripción

**Evercito** es un proyecto educativo enfocado en el aprendizaje y práctica del desarrollo de software utilizando tecnologías modernas.

Este repositorio incluye:

✅ Desarrollo Frontend  
✅ Desarrollo Backend  
✅ Bases de Datos  
✅ Interfaces Modernas  
✅ Programación Web  
✅ Diseño Responsivo  

---

# 🌐 Tecnologías Utilizadas

<table>
<tr>
<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" width="80"><br>
<b>HTML5</b>
</td>

<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" width="80"><br>
<b>CSS3</b>
</td>

<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="80"><br>
<b>JavaScript</b>
</td>
</tr>

<tr>
<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="80"><br>
<b>Java</b>
</td>

<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968350.png" width="80"><br>
<b>Python</b>
</td>

<td align="center">
<img src="https://cdn-icons-png.flaticon.com/512/2772/2772128.png" width="80"><br>
<b>SQL</b>
</td>
</tr>
</table>

---

# ⚙️ Funcionalidades

✨ Diseño moderno  
✨ Validaciones dinámicas  
✨ Interfaz responsiva  
✨ Manejo de bases de datos  
✨ Formularios interactivos  
✨ Organización profesional  

---

# 📂 Estructura del Proyecto

```bash
Evercito/
│
├── index.html
├── style.css
├── script.js
├── database.sql
├── README.md
│
├── assets/
│   ├── imagenes/
│   └── iconos/
```

---

# 📸 Vista del Proyecto

<div align="center">

<img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=1200&q=80" width="90%">

</div>

---

# 🎯 Objetivos

- Aprender programación
- Mejorar habilidades web
- Practicar bases de datos
- Crear proyectos modernos
- Dominar tecnologías actuales

---

# 👨‍💻 Autor

<div align="center">

<img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png" width="120">

## Antonio Mendez

### 🚀 Desarrollador en formación

</div>

---

# ⭐ Apoya el Proyecto

Si te gusta este repositorio puedes darle una ⭐ en GitHub.

---

<div align="center">

# 💙 Gracias por visitar mi perfil

### “El aprendizaje constante es la clave del éxito.”

</div>
