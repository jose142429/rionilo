# rionilo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://kit.fontawesome.com/d931934655.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="./style.css">
    <title>Rio Nilo</title>
</head>
<body>
    <!-- Esta parte es el inicio de html, lo que se pone cuando pones html:5, y el scrip es para que carguen los iconos de fontawesome -->
    
<header>
    <img src="./img/rio nilo logo.jpeg" alt="" width="100px" height="100px">
    <a href="#" class="logo" >RÍO <br> NILO</a>
    <ul class="navbar">
        <li><a href="#inicio">Inicio</a></li>
        <li><a href="#sobre_nosotros">Relación con Alejandría</a></li>
        <li><a href="#servicios">Productos del rio nilo</a></li>
    </ul>
</header>
<!-- El header sirve para la parte principal de la pagina donde puede ir tanto un logo, como tan solo un titulo y tambien esta la barra de navegacion que se hace por medio de  un menu para ir a las diferentes partes de la pagina.   -->
<section class="inicio" id="inicio">
   <div class="inicio-container">
    <div class="inicio-text">
        <span>Hola, Somos</span>
        <h1>RÍO NILO</h1>
        <h2>Pagina Oficial</h2>
        <p>El Nilo, un río que fluye hacia el norte en África, se encuentra entre las vías fluviales más largas del mundo, y es famoso por su antigua historia y los sitios arqueológicos que se encuentran a lo largo de sus orillas. El fértil Nilo inferior dio origen a la antigua civilización egipcia y aún alberga las Grandes Pirámides y la Esfinge de Guiza cerca de El Cairo. Las embarcaciones turísticas, desde lujosos cruceros hasta tradicionales falucas, también cruzan entre las ciudades de Luxor y Asuán. </p>
        <div class="buttons">
            <a href="./img/River-Nile-near-Aswan.jpg" class="btn">Conoce más sobre nosotros</a>
        </div>
    </div>
    <div class="inicio-img">
        <img src="./img/rio-nilo.png" alt="" width="100px" height="400px" >
    </div>
   
</div>
</section>
<!-- El section de inicio es todo lo que va a llevar el inicio, el texto, el span que es lo que primero se va a ver de texto osea lo principal, los h1 y h2 que son los titulos y el texto alternativo, y como lleva un boton ahi se utiliza la etiqueta a y en el href vas a poner ./y el link, luego va un class donde entre comillas esta btn que es lo primero que se hace para realizar dicho boton, el resto lo decoras en el style.css, luego del boton despues de esto:> va el texto o nombre que lleva el boton. -->
<!-- luego se inicia un div donde se pondra la imagen que estara al lado del texto, esta por medio de la etiqueta img. -->

<section class="sobre_nosotros" id="sobre_nosotros">
    <div class="heading">
        <h2>Relación con Alejandría</h2>
        <span>Río Nilo</span>
    </div>
    <div class="sobren-container">
        <div class="sobre-img">
            <img src="./img/59187de18793d1d95b56a498346fd651.jpg" alt="" width="100px" height="400px">
        </div>
        <div class="sobre-text">
         <p> Alejandría es el delta del Nilo constituye la desembocadura del río Nilo, en el mar Mediterráneo. Se   encuentra  en el norte de Egipto y se extiende sobre una superficie de aproximadamente 24.000 km².
         El delta del Nilo está formado por los brazos del río que se dividen en varios canales, que a su vez forman numerosas islas. El delta está dividido en dos partes: el occidental y el oriental. El occidental, en la margen izquierda del río, se extiende desde el Cairo hasta la ciudad de Rosetta. El oriental, en la margen derecha, se extiende desde el Cairo hasta la ciudad de Port Said.
             <br> </p>
            <br>
            <a href="./img/Sin-titulo.jpg" class="btn">CONECCION CON EL NILO</a>
            
        
        </div>
        </div>
</div>
</section>
<!-- El segundo section es para la parte siguiente de la pagina donde es casi lo mismo que la primera, un span como lo principal y el h2 como el titulo de la pagina, luego esta un div con el class de imagen donde va la imagen con el texto, en este caso va primero la imagen para que quede al otro lado de la que quedo la primera, luego va el texto y por ultimo el boton que se hace como lo explique en el primer section. -->
<!-- si le quieren agregar mas seria por medio de otro div y lo que quieras agregar. -->



<section  class="servicios" id="servicios">
    <div class="heading">
        <h2>Ropa del Nilo</h2>
        <p>
           Estos productos los vendemos, para que la gente porte algo en honor a Egipto, el Nilo y ciudades como Alejandría, con esto economicamente podemos mejorar la página y brindar una mejor atención a la gente que visita nuestro sitio web.
        </p>
    </div>

    <div class="servicios-content">
        <div class="servicios-box">
            <img src="./img/camiseta.jpg" alt="" width="200px" height="200px">
            <h3>Camiseta</h3>
            <a href="#" class="box">Más Informacion</a>
        </div>

        <div class="servicios-box">
            <img src="./img/hoodie.jpg" alt="" width="200px" height="200px">
            <h3>Busos</h3>
            <a href="#" class="box">Más Informacion</a>
        </div>

        <div class="servicios-box">
            <img src="./img/alejandria.jpg" alt="" width="200px" height="200px" >
            <h3>Blusas</h3>
            <a href="#" class="box">Más Informacion</a>
        </div>

    </div>
</section>
<!-- En el tercer section va los servicios o donde estaran las tarjetas de lo que ofreces en la pagina, primero iria el span o lo principal de esta parte y luego el h2 que es el  titulo de esta parte, luego va un  div y un class donde iria el contenido de las tarjeta y el icono de fontawsome que escojas, por cado uno va un segundo div por el cual esta "servicios-box" que es donde iria el icono el nombre y el texto alternativo que lleva cada tarjeta. -->
<footer>
    <div class="footer">
    <div class="copyright">
        <p>RÍO NILO | Derechos reservados 2023 <i class="fa-regular fa-copyright"></i></p>
    </div>
</footer>
<!-- Por ultimo esta el footer que es lo ultimo que se ve en la pagina, este se hace por medio de un div-class=footer y un class=copyright para evitar que la pagina sea copiada en este copyright va el nombre de tu pagina, los derechos reservados y el año en que hiciste la pagina. -->
</body>
</html
