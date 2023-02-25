<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto-final</title>
    <link rel="stylesheet" href="Style/myEstilo.css">
    <script src="/script.js/eventos.js"></script>
    <!--el ccs y el js estan echos asi porque el visual studio code no me carga si le hago otras carpetas y no entiendo porque-->
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;1,100;1,300;1,400&display=swap');

    </style>

</head>
                        <!--Acá empieza la botonera lateral-->
<div class="botonera">
    <a href="#personal"><img class="boton" src="img/personal.png" id="pers" onmousemove="enAmarillo1()" onmouseleave="enNegro1()" alt="informacion personal"> </a>
    <a href="#laboral"><img class="boton" src="img/laboral.png" id="labo" onmousemove="enAmarillo2()" onmouseleave="enNegro2()" alt="informacion laboral"> </a>
    <a href="#habilidades"><img class="boton" src="img/habilidades.png" id="habi" onmousemove="enAmarillo3()" onmouseleave="enNegro3()" alt="habilidades"> </a>
    <a href="#educacion"><img class="boton" src="img/estudios.png" id="estu" onmousemove="enAmarillo4()" onmouseleave="enNegro4()" alt="estudios"> </a>
</div>
<body>
                        <!--Acá empieza lo principal del CV-->
<div class="degrade">
    <div class="grilla">
<div class="intro">
    <div class="nombres">Figueredo Marcos</div>
    <div class="bajada">Tecnico Mecanico</div>
    <div class="descripcion"></div>
    <a href="#"><img src="img/behance.png" class="icono" id="be" onmousemove="enAmarillo5()" onmouseleave="enNegro5()"></a>
    <a href="https://github.com/Marcos-Figueredo"><img src="img/github.png" class="icono" id="gi" onmousemove="enAmarillo6()" onmouseleave="enNegro6()"></a>
    <a href="#"><img src="img/linkedin.png" class="icono" id="li" onmousemove="enAmarillo7()" onmouseleave="enNegro7()"></a>
</div>
    <img src="img/marcos.png" class="perfil">
    </div>
</div> <!--Acá termina lo principal del cv-->
                        <!--Acá empieza el contenido del CV-->  
<div class="caja"  id="personal">
    <div class="titulo">Información Personal</div>
    <div class="text">    
        <ul>
            <li>Edad: 26</li>
            <li>Residencia: Villa Constitucion</li>
            <li>Nacimiento: 11/09/1996</li>
            <li>Nacionalidad: Argentina</li>
            <li>Telefono: 3400-537204</li>
            <li>E-mail: figueredomarcoss00@gmail.com</li>
        </ul>
    </div>
</div>
    
<div class="caja" id="laboral">
    <div class="titulo">Experiencia Laboral</div>
    <div class="text">    
        <ul>
            <li>2016 - 2020 / Metalcar SRL / Operario de fresa; torno; limadora y alesadora convencional</li>
            <li>2020 - 2023 / Metalurgica Galli / Operario CNC</li>
        </ul>
    </div>
</div>
    
<div class="caja" id="habilidades">
    <div class="titulo">Habilidades</div>
    <div class="text">    
        <ul>
            <li>HTML</li>
            <li>CSS</li>
        </ul>
    </div>
</div>

<div class="caja" id="educacion">
    <div class="titulo">Estudios</div>
    <div class="text">    
        <ul>
            <li>2010 - 2016 / Tecnico Mecanico / Instituto San Pablo 2073</li>
            <li>2018 - 2019 / Curso de Perito Clasificador de Granos / Escuela de Recibidores de Granos</li>
            <li>2023 / Cursos virtuales de desarrollo front-end</li>
        </ul>
    </div>
</div>
<div class="vacio"></div>
</cuerpo >
</body>
</html>