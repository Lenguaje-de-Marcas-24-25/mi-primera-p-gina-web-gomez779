# Ejercicio HTML 1

## Desarrolla una página web sobre HTML5 utilizando los siguientes elementos:

* Elementos de texto: títulos, párrafos, saltos de línea
* Al menos una lista anidada
* Mínimo 1 tabla con cabecera y 3 columnas.
* 1 imágen del centro
* Hipervínculos

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        h1 {
            font-size: 2em;
        }
        h2 {
            font-size: 1.5em;
        }
        ul {
            list-style-type: circle;
        }
        a {
            color: blue;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        img {
            width: 150px;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>HTML</h1>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/61/HTML5_logo_and_wordmark.svg" alt="HTML5 Logo">
    <h2>¿Qué es HTML?</h2>
    <p>
        HTML, sigla en inglés de <strong>HyperText Markup Language</strong> (lenguaje de marcas de hipertexto), 
        hace referencia al lenguaje de marcado para la elaboración de páginas web. 
        Es un estándar que sirve de referencia del software que conecta con la elaboración de páginas web en sus diferentes versiones, 
        define una estructura básica y un código (denominado código HTML) para la definición de contenido de una página web, 
        como texto, imágenes, videos, juegos, entre otros.
    </p>
    <p>
        Para más detalles haz click en <a href="https://es.wikipedia.org/wiki/HTML">este enlace</a>
    </p>
    <h2>Editores de texto recomendados</h2>
    <p>Algunos editores de texto recomendados son:</p>
    <ul>
        <li>Notepad
            <ul>
                <li><a href="https://notepad-plus-plus.org/downloads/">Enlace para descargar</a></li>
            </ul>
        </li>
        <li>SublimeText
            <ul>
                <li><a href="https://www.sublimetext.com/3">Enlace para descargar</a></li>
            </ul>
        </li>
        <li>Dreamweaver
            <ul>
                <li><a href="https://www.adobe.com/products/dreamweaver.html">Enlace para descargar</a></li>
            </ul>
        </li>
        <li>Gedit
            <ul>
                <li><a href="https://wiki.gnome.org/Apps/Gedit">Enlace para descargar</a></li>
            </ul>
        </li>
        <li>Notepad++
            <ul>
                <li><a href="https://notepad-plus-plus.org/downloads/">Enlace para descargar</a></li>
            </ul>
        </li>
    </ul>
    <h2>Navegadores Web</h2>
    <p>Los siguientes navegadores permiten visualizar páginas web:</p>
    <ul>
        <li>Firefox - <a href="https://www.mozilla.org/es-ES/firefox/new/">Descargar</a></li>
        <li>Microsoft Edge - <a href="https://www.microsoft.com/es-es/edge">Descargar</a></li>
        <li>Google Chrome - <a href="https://www.google.com/intl/es/chrome/">Descargar</a></li>
        <li>Safari - <a href="https://www.apple.com/safari/">Descargar</a></li>
    </ul>
</body>
</html>

[index.html](index.html)
[index2.html](index2.html)
