# GaboBIT
Proyecto realizado para el Bootcamp Desarrollo Web Full Stack de BIT, donde se explica como crear una página web básica solo usando HTML y CSS sin ningun framework para comprender las báses de estas dos herramientas.




# HTML

<!DOCTYPE html>: Indica que este es un documento HTML5.

<html>: Define el comienzo del documento HTML.

<head>: Define la sección del documento que contiene información del encabezado, como los metadatos y los enlaces a archivos CSS y JS.

<meta charset="UTF-8" />: Define el juego de caracteres utilizado en el documento como UTF-8.

<meta http-equiv="X-UA-Compatible" content="ie=edge" />: Define la compatibilidad con versiones anteriores de Internet Explorer.

<meta name="viewport" content="width=device-width, initial-scale=1.0" />: Define el tamaño de la ventana gráfica visible de la página web para dispositivos móviles.

<link rel="stylesheet" href="./css/style.css" />: Enlaza el archivo CSS de estilo con la página HTML.

<link rel="preconnect" href="https://fonts.googleapis.com" />: Preconecta con el dominio de la API de Google Fonts para mejorar la velocidad de carga de las fuentes.

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />: Preconecta con el dominio de los archivos de fuentes de Google Fonts para mejorar la velocidad de carga de las fuentes.

<link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap" rel="stylesheet" />: Enlaza la fuente "Libre Baskerville" de Google Fonts con la página HTML.

<title>Gabo BIT</title>: Define el título de la página en la pestaña del navegador.

<header class="header">: Define un encabezado que se utiliza para mostrar el logo y el menú de navegación de la página. La clase "header" se utiliza para definir su estilo en CSS.

<div class="logo">: Define un contenedor para el logotipo de la página. La clase "logo" se utiliza para definir su estilo en CSS.

<a href="index.html">: Define un enlace al inicio de la página. Cuando se hace clic en el enlace, se redirige al usuario a la página de inicio. El atributo "href" indica la ubicación de la página de inicio.

<img src="./img/logo.png" alt="Logo de Gabo" width="80" height="50" />: Define una imagen que se utiliza como logotipo de la página. El atributo "src" indica la ubicación de la imagen. Los atributos "width" y "height" especifican el ancho y la altura de la imagen.

<nav class="menu">: Define un elemento de navegación que se utiliza para mostrar el menú de navegación de la página. La clase "menu" se utiliza para definir su estilo en CSS.

<ul>: Define una lista desordenada que contiene los elementos del menú de navegación.

<li>: Define un elemento de lista que contiene un enlace del menú de navegación.

<a href="https://es.wikipedia.org/wiki/Wikipedia:Portada" target="_blank">Categorías</a>: Define un enlace del menú de navegación que redirige al usuario a la página de Wikipedia. El atributo "target" indica que el enlace se abrirá en una nueva pestaña del navegador.

<a href="https://es.wikipedia.org/wiki/Wikipedia:Portada">Biografía</a>: Define un enlace del menú de navegación que redirige al usuario a la página de Wikipedia.

<a href="https://es.wikipedia.org/wiki/Wikipedia:Portada">Premios</a>: Define un enlace del menú de navegación que redirige al usuario a la página de Wikipedia.


La etiqueta <meta> se utiliza para proporcionar información adicional sobre la página web en el encabezado HTML. Se pueden utilizar varias etiquetas meta para proporcionar diferentes tipos de información, como el autor del sitio web, palabras clave relevantes para el contenido de la página, descripción del contenido de la página, la codificación de caracteres utilizada, la vista previa de la página web en redes sociales, etc.

Algunos de los atributos más comunes que se usan con la etiqueta <meta> son charset, name, content, http-equiv, y viewport. El atributo charset define el juego de caracteres utilizado en la página web, el atributo name se usa para definir nombres de metadatos personalizados, el atributo content se utiliza para proporcionar el contenido asociado con los metadatos, el atributo http-equiv se utiliza para especificar información adicional que puede ser utilizada por los navegadores web o motores de búsqueda, y el atributo viewport se utiliza para definir la ventana gráfica visible de la página web en dispositivos móviles.
  
  # CSS

*: Es un selector universal que se aplica a todos los elementos de la página web. En este caso, se establecen ciertas propiedades en cero para asegurar que no haya márgenes, rellenos y que la fuente sea la especificada.

margin: 0;: Define el margen del elemento, que en este caso se establece en 0, lo que significa que no hay ningún margen alrededor de ningún elemento.

padding: 0;: Define el relleno del elemento, que en este caso se establece en 0, lo que significa que no hay ningún relleno dentro de ningún elemento.

font-family: "Libre Baskerville", serif;: Establece la familia de fuentes para todos los elementos de la página. En este caso, se utiliza "Libre Baskerville" como fuente principal y "serif" como fuente secundaria.

body: Se aplica a todo el cuerpo de la página, estableciendo su estilo.

font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;: Establece la familia de fuentes para el texto del cuerpo de la página. En este caso, se utilizan varias fuentes diferentes en caso de que alguna de ellas no esté disponible en el sistema del usuario.

background-color: #b4c2dd;: Establece el color de fondo del cuerpo de la página en un tono de azul claro.

.header: Hace referencia a la clase "header" en el HTML, que es un elemento específico de la página, como un encabezado. Se establece su altura y color de fondo.

height: 70px;: Establece la altura de la sección de encabezado en 70 píxeles.

background-color: #c48424;: Establece el color de fondo de la sección de encabezado en un tono marrón.

.logo: Hace referencia a la clase "logo" en el HTML, que se utiliza para definir el estilo de un logotipo. Se establece que este logotipo flote a la izquierda y tenga un relleno de 10 píxeles.

.menu: Hace referencia a la clase "menu" en el HTML, que se utiliza para definir el estilo de un menú de navegación.

float: right;: Establece que el elemento "menu" flote a la derecha.

margin: 24px;: Establece un margen de 24 píxeles alrededor del elemento "menu".

.menu ul: Se aplica a la lista desordenada (ul) dentro del elemento "menu".

list-style: none;: Elimina los puntos de la lista desordenada y los sustituye por un guion.

.menu li: Hace referencia a cada elemento de la lista en el menú de navegación.

display: inline-block;: Establece que los elementos de la lista se muestren en una línea horizontal y puedan ser afectados por margenes y paddings.

margin-right: 10px;: Establece un margen de 10 píxeles a la derecha de cada elemento de la lista, excepto el último.

.menu a: Hace referencia a los enlaces dentro de cada elemento de la lista en el menú de navegación.

color: black;: Establece el color del texto de los enlaces a negro.

text-decoration: none;: Elimina el subrayado predeterminado de los enlaces.

padding: 15px;: Establece un relleno de 15 píxeles alrededor de cada enlace en el menú de navegación.

font-weight: bold;: Establece la fuente en negrita para los enlaces en el menú de navegación.

