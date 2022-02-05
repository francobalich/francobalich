<!DOCTYPE html>
<html lang="es">

<head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="src/css/styles.css">
</head>

<body>
        <img src="/src/img/foto-de-perfil.png" alt="" srcset="">
        <h1>Hola, Soy Franco Balich <img src="src/img/Hi.gif" alt=""></h1>
        <h2>Este es mi GitHub💻</h2>
        <p>Acá podrás encontrar varios proyectos en los que me encuentro trabajando, algunos de es estos son sobre: Python, Desarrollo Web, Inteligencia Artificial, ASP y Unity.</p>
        <h2>Mi videos de YouTube</h2>
        <div class="videoContainer">
                <a class="videoYoutube" href="https://www.youtube.com/watch?v=EffObMj6BKA" target="blank"><img
                                src="src/img/Aprende sobre robotica.png" alt=""></a>
                <a class="videoYoutube" href="https://www.youtube.com/watch?v=E-JSfQysTK8" target="blank"><img
                                src="src/img/evento robots.png" alt=""></a>
        </div>
        <h2>Videos de mi emprendimiento</h2>
        <div class="videoContainer">
                <a class="videoYoutube" href="https://www.youtube.com/watch?v=oef3IxmZKYo" target="blank"><img
                                src="src/img/Aprende sobre robotica y programacion.png" alt=""></a>
                <a class="videoYoutube" href="https://www.youtube.com/c/InnovativaLab/videos" target="blank"><img
                                src="src/img/aprende sobre tinkercad.png" alt=""></a>
        </div>
        <style>
                h1 img{
                        width:30px;
                }
                .videoContainer {
                        display: flex;
                        flex-direction: row;
                }

                .videoYoutube {
                        display: inline-block;
                }

                .videoYoutube img {
                        width: 90%;

                }
        </style>
</body>

</html>