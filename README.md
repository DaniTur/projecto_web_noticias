# Proyecto_web_noticias

https://rawgit.com/DaniTur/projecto_web_noticias/master/news.html

## Notas de cambios:

- Se ha añadido un botón para cargas más noticias aparte de las 3 estáticas.
- Se ha añadido la funcionalidad de cargar noticias haciendo scroll con un botón propio.
- La publicidad ahora puede ser rotatoria.
- Ahora el texto del boton cambia a “No hay más noticias” cuando no hay noticias para cargar
- Se ha eliminado la palabra link que se repetía en todos los artículos
- Se ha añadido una transición de carga mientras se cargan las noticias
- Se ha corregido un error que hacía peticiones y cargas innecesarias de ficheros.
- Las etiquetas de Open Graph ahora coinciden con las meta del HTML.
- Se ha introducido el enlace al fichero rss.xml
- Se ha mejorado el código para que no se repitan trozos de código idénticos mejorando el rendimiento.

## Descripción
En este proyecto utilizaremos las herramientas: HTML 5, CSS 3, jQuery , Bootstrap 5.

Primero hacemos un diseño a mano de las indicaciones que nos dan para hacer el proyecto.
Esto sería el dibujo de los artículos de la versión base:





Este es el dibujo general de la primera versión de escritorio:


Este es el dibujo general de la primera versión de smartphones:






 Luego pensamos y dibujamos el diseño por capas del proyecto. Una versión para escritorio y para móvil de la pagina inicial y una versión para escritorio y móvil de la pagina individual de cada noticia completa.

Utilizando las librerías de Bootstrap 3 hacemos una plantilla básica de HTML y CSS de la página inicial tanto en móvil como en escritorio.

A continuación modificamos la plantilla básica de Bootstrap, añadimos y retocamos todo lo necesario para que quede como en el diseño de capas dibujado. La posición exacta de los artículos, espacio publicitario, encabezado y  demás cosas, al no estar especificadas, las ponemos como a nosotros nos parezca adecuado.

Ahora crearemos las páginas para las noticias individuales, de la misma manera que antes, primero haremos una plantilla básica con Bootstrap y la modificaremos para que quede como el diseño dibujado haciendo los retoques necesarios para que las interacciones entre elementos al ajustar diferentes tamaños de pantalla funcionen correctamente y queden limpios.


Cuando ya tenemos los diseños hacemos el espacio para la publicidad dandole un margen fijo a la derecha del contenido y ese sera el espacio publicitario.

Al terminar esto empezé a escribir el javascript de la web con jQuery que simplifica bastante el código a escribir, el proyecto cuenta con diferentes funciones:
- Boton para cargar más noticias desde diferentes archivos JSON
- Boton para cambiar entre cagar nocitias con escroll Activado/Desactivado
- Cargar noticias al hacer scroll
- Publicidad rotatória
- Pequeña pantalla de carga al clicar en el botón.

by Dani Tur Zurita
