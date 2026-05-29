<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    height:100vh;
    overflow:hidden;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#020617,#0f172a,#1e293b);
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
    animation:fondo 15s linear infinite;
    opacity:0.25;
}

@keyframes fondo{

    0%{
        transform:translate(0,0);
    }

    100%{
        transform:translate(-120px,-120px);
    }

}

/* Caja principal */

.box{
    width:450px;
    height:250px;
    border-radius:30px;
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(12px);
    position:relative;

    box-shadow:
    0 0 20px #38bdf8,
    0 0 40px #9333ea,
    0 0 70px #22c55e;

    animation:flotar 4s ease-in-out infinite;
}

@keyframes flotar{

    0%,100%{
        transform:translateY(0px);
    }

    50%{
        transform:translateY(-12px);
    }

}

/* Luces */

.light{
    position:absolute;
    border-radius:50%;
    filter:blur(20px);
    animation:mover 10s linear infinite alternate;
}

.light1{
    width:180px;
    height:180px;
    background:#38bdf8;
    top:-50px;
    left:-60px;
}

.light2{
    width:200px;
    height:200px;
    background:#9333ea;
    bottom:-60px;
    right:-60px;
}

.light3{
    width:120px;
    height:120px;
    background:#22c55e;
    top:40%;
    left:40%;
}

@keyframes mover{

    from{
        transform:translateY(0px);
    }

    to{
        transform:translateY(-40px);
    }

}

/* Líneas decorativas */

.line{
    position:absolute;
    background:linear-gradient(90deg,transparent,#38bdf8,transparent);
    height:2px;
    width:100%;
    animation:linea 3s linear infinite;
}

.line1{
    top:20%;
}

.line2{
    top:50%;
}

.line3{
    top:80%;
}

@keyframes linea{

    0%{
        transform:translateX(-100%);
    }

    100%{
        transform:translateX(100%);
    }

}

</style>
</head>

<body>

<div class="light light1"></div>
<div class="light light2"></div>
<div class="light light3"></div>

<div class="box">
    <div class="line line1"></div>
    <div class="line line2"></div>
    <div class="line line3"></div>
</div>

</body>
</html>

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
