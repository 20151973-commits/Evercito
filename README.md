<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Evercito Developer</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    background:#0f172a;
    overflow:hidden;
}

/* FONDO */

.container{
    width:100%;
    height:100vh;
    position:relative;
    display:flex;
    justify-content:center;
    align-items:center;
}

/* IMAGEN PRINCIPAL */

.dev{
    width:450px;
    animation:flotar 4s ease-in-out infinite;
    filter:drop-shadow(0px 0px 30px #38bdf8);
}

/* EFECTOS */

.circle{
    position:absolute;
    border-radius:50%;
    background:rgba(56,189,248,0.2);
    animation:mover 10s linear infinite;
}

.circle:nth-child(1){
    width:300px;
    height:300px;
    top:10%;
    left:10%;
}

.circle:nth-child(2){
    width:200px;
    height:200px;
    bottom:10%;
    right:10%;
}

.circle:nth-child(3){
    width:150px;
    height:150px;
    top:50%;
    left:70%;
}

/* ANIMACIONES */

@keyframes flotar{
    0%{
        transform:translateY(0px);
    }
    50%{
        transform:translateY(-20px);
    }
    100%{
        transform:translateY(0px);
    }
}

@keyframes mover{
    0%{
        transform:scale(1) rotate(0deg);
    }
    50%{
        transform:scale(1.2) rotate(180deg);
    }
    100%{
        transform:scale(1) rotate(360deg);
    }
}

</style>

</head>
<body>

<div class="container">

<div class="circle"></div>
<div class="circle"></div>
<div class="circle"></div>

<img 
class="dev"
src="https://cdn-icons-png.flaticon.com/512/6062/6062646.png"
alt="Developer">

</div>

</body>
</html>
