<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Examen Jeremy Martinez</title>
    <link rel="stylesheet" href="./css/index.css">
    <script src="https://use.fontawesome.com/releases/v5.15.4/js/all.js" data-auto-a11y="true"></script>
</head>

<body>


    <body>

        <div class="header">
            <div class="column1"><img src="./img/guantes.jpeg" alt="guantes" id="img1"></div>
            <div class="column1">Examen Lenguaje de Marcas <br>
                <div id="pk">1ºEvaluación</div>
            </div>
            <div class="column1">
                <label for="fname" id="pos">Buscar:</label>
                <input type="text" id="fname" name="fname" value="Introduce un texto"><br>
            </div>
        </div>

        <div class="row">
            <div class="column2">
                <ul>
                    <li><a href="#final">Boxeadores</a></li>
                    <li><a href="https://www.marca.com/" target="_blank">Prensa</a></li>
                    <li><a href="#contact">Sobre mí</a></li>
                </ul>
            </div>
            <div class="column2">
                <div class="loma">Lomachenko:</div><br><iframe src="https://www.youtube.com/embed/VA8I1NxoQOk"
                    title="YouTube video player" frameborder="0"
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen id="vid"></iframe>
            </div>
            <div class="column2">
                <div class="loma">Subscribirse:</div><br>
                <form action="http:// jkorpela.fi/cgi-bin/echo.cgi" method="post">
                    <label for="apellido">Apellidos</label>
                    <input type="text" id="apellido" name="apellido" placeholder="Ingrese su apellido"><br><br>
                    <label for="lname">Nombre</label>
                    <input type="text" id="lname" name="lname" placeholder="Ingrese su nombre"><br><br>

                    <label for="nac">Nacionalidad:</label>
                    <select id="nac" name="nacionalidad">
                        <option value="Armenia">Armenia</option>
                        <option value="España" selected> España</option>
                        <option value="Francia">Francia</option>
                        <option value="Italia">Italia</option>
                        <option value="Portugal">Portugal</option>
                    </select><br><br>
                    <label for="email">E-Mail</label>
                    <input type="email" id="email" name="email" placeholder="Ingrese su E-Mail"><br><br>
                    <label for="contraseña">Contraseña</label>
                    <input type="password" id="contra" name="contraseña" placeholder="Ingrese su contraseña"><br><br>
                    <label for="html">Sexo</label>

                    <input type="radio" id="Mas" name="fav_language" value="Masculino">
                    <label for="M">M</label>
                    <input type="radio" id="Fem" name="fav_language" value="Femenino">
                    <label for="F">F</label><br><br>
                    <input type="checkbox" id="checkbox" name="verificacion" checked>
                    <label for="vehicle1"> Deseo recibir mas información a través de este correo electrónico</label><br><br>


                    <input type="submit" value="Enviar" id="sub">
                    <input type="reset" value="Restablecer" id="sub1">

                </form>
            </div>
            <div class="column2">
                <table>
                    <tr>
                    <th  colspan="3">Boxeadores</th>
                    </tr>
                      <tr>
                        <th>Nombre</th>
                        <th>Nacimiento</th>
                        <th>Peso</th>
                      </tr>
                      <tr>
                        <td>Muhhamad Ali</td>
                        <td>17 de Enero de 1942</td>
                        <td>Pesado</td>
                      </tr>
                      <tr>
                        <td>Marian Trimiar</td>
                        <td>15 de Agosto de 1953</td>
                        <td>Pesado</td>
                      </tr>  <tr>
                        <td>Vasyl Lomachenko</td>
                        <td>17 de febrero de 1988</td>
                        <td>Welter</td>
                      </tr>
                    </table>
            </div>
        </div><br><br><br><br><br><br>
            
    <div id="extra">
        <span id="boxeotexto">El boxeo (del inglés boxing), también llamado a veces boxeo inglés, boxeo irlandés o pugilismo, y comúnmente conocido como box, es un deporte de contacto en el que dos contrincantes luchan utilizando únicamente sus puños con guantes, golpeando a su adversario de la cintura hacia arriba, dentro de un cuadrilátero especialmente diseñado para tal fin; la pelea se lleva a cabo en breves secuencias de lucha denominadas asaltos y de acuerdo a un preciso reglamento, el cual regula categorías de pesos y duración del encuentro, entre otros aspectos. De un modo más general, boxeo o "boxing" se refiere a un amplio género de deportes de combate en las que dos oponentes se enfrentan en lucha utilizando los puños, tapados por guantes y diferenciándose según sus reglas diferentes deportes como el ya mencionado boxeo inglés o boxeo propiamente dicho, el boxeo francés o savate, el boxeo chino o boxeo Shaolín, el kick boxing o boxeo japonés, el muay thai o boxeo tailandés, el suntukan o boxeo filipino, y los antiguos estilos de pugilato griegos como el pygmachia y el pancracio.</span>
        <div id="boxeadores">
            <div class="gallery">
                <a target="_blank" href="img_forest.jpg">
                <img src="IMG/ali.jpeg" alt="Forest" width="600" height="400">
                </a>
            </div>
            <div class="gallery">
                <a target="_blank" href="img_lights.jpg">
                <img src="IMG/lomachenko.jpeg" alt="Northern Lights" width="600" height="400">
                </a>
            </div>
            <div class="gallery">
                <a target="_blank" href="test">
                <img src="IMG/ladytyger.jpeg" alt="ladytyger" width="600" height="400">
                </a>
            </div>
            <div id="final"></div>
        </div>
    </div>

        <div class="footer">
            <div class="fot1"><i class='far'>&#xf1f9;</i>Todos los derechos reservados</div>
            <div class="fot1">Siguenos en las redes <hr> <i class="fab fa-twitter"></i>
            <i class="fab fa-facebook-square"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-tiktok"></i></div>
            <div class="fot1"> Web realizada por Jeremy Martinez Rogel</div>
 
        </div>

    </body>

</html>
