<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css" integrity="sha512-xh6O/CkQoPOWDdYTDqeRdPCVd1SpvCA9XXcUnZS2FmJNp1coAFzvtCN9BmamE+4aHK8yyUHUSCcJHgXloTyT2A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="./CSS/INICIO.css">
    <title>Document</title>
</head>
<body>
    <!--SECCION INICIO-->
    <section id="inicio">
        <div class="contenido">
            <header>
                <div class="contenido-header">
                    <h1>/LP/</h1>
                    <nav id="nav" class="">
                        <ul id="links">
                            <li><a href="#inicio" class="seleccionado">Inicio</a></li>
                            <li><a href="#sobremi">Sobre Mi</a></li>
                            <li><a href="#Servicios">Servicios</a></li>
                            <li><a href="#Portafolio">Portafolio</a></li>
                            <li><a href="#contacto">Contacto</a></li>
                        </ul> 
                    </nav>
                    <!--ICONOS DEL MENU RESPONSIVE-->
                    <div id="icono-nav" onclick="responsiveMenu()">
                        <i class="fa-solid fa-bars"></i>
                    </div>
                    <!--ICONOS DE LAS REDES SOCIALES-->
                    <div class="redes">
                        <a href="#"><i class="fa-brands fa-square-instagram"></i></i></a>
                        <a href="#"><i class="fa-brands fa-facebook"></i></a>
                        <a href="#"><i class="fa-brands fa-google"></i></a>
                    </div>
                </div>
            </header>
            <div class="presentacion">
                <p class="bienvenida">bienvenidos</p>
                <h2>Soy <span>Diego Camargo</span>, desarrollador Web</h2>
                <p class="descripcion">Hola soy Diego Alexander Camargo Ramirez desarrollador web con un año de experiencias en el area,me especializo en la parte del Front-end utilizando HTML5, CSS3 y JavaScript</p>
                <a href="#Portafolio">Ir a Portafolio</a>
            </div>
        </div>
    </section>
    
    <!--SELECCION SOBRE MI-->
    <section id="sobremi">
        <div class="contenedor-foto">
            <img src="./Imagenes/Avatar.jpg" alt="">
        </div>
        <div class="sobremi">
            <p class="titulo-seccion">Sobre mi</p>
            <h2>hola, soy <span>Diego Camargo</span></h2>
            <h3>Desarrollador Web</h3>
            <p>Me gusta trabajar en equipo, la responsabilidad y el respeto de mi hacia mis compañeros.</p>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <a href="#">Descarga de CV</a>
        </div>
    </section>

    <!--SECCION SERVICIOS-->
    <section id="Servicios">
        <h3 class="titulo-seccion">Mis Servicios</h3>
        <div class="fila">
            <div class="servicio">
                <div class="icono"><i class="fa-solid fa-code"></i></div>
                <h4>HTML5</h4>
                <hr>
                <ul class="servicio-tag">
                    <li>graficos</li>
                    <li>web</li>
                    <li>Seo</li>
                </ul>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            </div>
            <div class="servicio">
                <div class="icono"><i class="fa-solid fa-code"></i></div>
                <h4>CSS3</h4>
                <hr>
                <ul class="servicio-tag">
                    <li>graficos</li>
                    <li>web</li>
                    <li>Seo</li>
                </ul>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            </div>
            <div class="servicio">
                <div class="icono"><i class="fa-solid fa-code"></i></div>
                <h4>JavaScript</h4>
                <hr>
                <ul class="servicio-tag">
                    <li>graficos</li>
                    <li>web</li>
                    <li>Seo</li>
                </ul>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</p>
            </div>
        </div>
    </section>

    <!--SECCION HABILIDADES-->
    <div class="contenedor-skills" id="skill">
        <h3>Habilidades</h3>
        <div class="skill">
            <div class="info">
                <p><span class="lista"></span>HTML5 & CSS3</p>
                <span class="porcentaje">95%</span>
            </div>
            <div class="barra">
                <div id="html" class="barra-prrgreso1"></div>
            </div>
        </div>

        <div class="skill">
            <div class="info">
                <p><span class="lista"></span>JavaScript</p>
                <span class="porcentaje">85%</span>
            </div>
            <div class="barra">
                <div id="js" class="barra-prrgreso2"></div>
            </div>
        </div>

        <div class="skill">
            <div class="info">
                <p><span class="lista"></span>Bases de Datos</p>
                <span class="porcentaje">50%</span>
            </div>
            <div class="barra">
                <div id="bd" class="barra-prrgreso3"></div>
            </div>
        </div>
    </div>

    <!--SELECION  PORTAFOLIO-->
    <section id="Portafolio">
        <h3 class="titulo-seccion">MIS PROYECTOS</h3>
        <div class="fila">
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="./Imagenes/2.jpg" alt="">
                <div class="info">
                    <h4>Descripcion del proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="./Imagenes/2.jpg" alt="">
                <div class="info">
                    <h4>Descripcion del proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
            <div class="proyecto">
                <div class="overlay"></div>
                <img src="./Imagenes/2.jpg" alt="">
                <div class="info">
                    <h4>Descripcion del proyecto</h4>
                    <p>Diseño Web</p>
                </div>
            </div>
        </div>
    </section>

    <!--SECCION CONTACTO-->
    <selection id="contacto">
        <h3 class="titulo-seccion">contactanos ahora</h3>
        <div class="contenedor-form">
            <form action="button">
                <div class="mitad">
                    <input type="text" placeholder="Nombre Completo" class="input-mitad">
                    <input type="text" placeholder="Direccion E-mail" class="input-mitad">
                </div>
                <div class="fila">
                    <input type="text" placeholder="Tema.." class="input-full">
                </div>
                <div class="fila">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Tu Mensaje" class="input-full"></textarea>
                </div>
                <input type="button" value="Enviar Mensaje" class="btn-enviar">
            </form>
        </div>
    </selection>

    <!--SECCION FOOTER-->
    <footer>
        <p>Todos los derechos reservados</p>
        <div class="redes">
            <a href="#"><i class="fa-brands fa-square-instagram"></i></i></a>
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-google"></i></a>
        </div>
    </footer>

    <Script src="./JS/INICIO.js"></Script>
</body>
</html>
