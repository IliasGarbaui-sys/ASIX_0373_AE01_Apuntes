# ASIX_0373_AE01_Apuntes
Apuntes del curso. Primera parte.

Apuntes de Lenguajes de Marcas y Sistemas de Gestión de Información

Este repositorio contiene todos los apuntes que voy haciendo durante la asignatura, incluyendo la teoría y las actividades prácticas que realizamos en clase. Aquí voy registrando todo lo aprendido sobre GitHub, Markdown y HTML.

Índice de contenidos

1.GitHub

2.Markdown

3.HTML

GitHub

En clase aprendimos qué es GitHub y para qué sirve. Básicamente, GitHub sirve para guardar nuestros proyectos y poder ver todos los cambios que hacemos. También nos permite trabajar en grupo sin liarnos y mantener un historial de los cambios que realizamos.

Primero instalé Git desde su página oficial. Después configuré mi nombre y mi correo para que quede registrado quién hace los cambios en el repositorio. Aprendí que la rama principal de los proyectos puede llamarse main o master, dependiendo de la versión de Git, y que se puede cambiar si quieres.

Luego creé un repositorio nuevo en GitHub. Elegí si quería que fuera público o privado y si quería añadir un archivo README desde el principio. También aprendí la diferencia entre un repositorio vacío y uno inicializado, y cómo esto cambia la forma de trabajar en local.

Para trabajar en mi ordenador con un repositorio que ya estaba en GitHub, lo cloné, entré en la carpeta y fui haciendo los cambios. Cada vez que añadía cosas, las guardaba con un commit y luego subía todo al repositorio de GitHub para que se actualizara. También aprendimos a crear repositorios desde cero en local y luego vincularlos con un repositorio de GitHub. Aprendí a importar proyectos que ya existían de otras personas y, al final, a publicar todo en GitHub Pages para que se pudiera ver online. Con esto entendí cómo organizar los archivos, trabajar en local y remoto, y publicar proyectos para que cualquiera pueda verlos.

Markdown

En clase aprendimos qué es Markdown y para qué sirve. Markdown es un lenguaje de marcas que nos permite dar formato a los textos de manera sencilla sin usar programas complicados. Podemos crear títulos, listas, enlaces, imágenes y resaltar texto fácilmente.

Encabezados

Los encabezados se hacen con # y sirven para los títulos:

# → título grande

## → título un poco más pequeño

### → título todavía más pequeño

Estilos de letra

Cursiva: *texto*

Negrita: **texto**

Tachado: ~~texto~~

Listas

Listas ordenadas

Se hacen con números y no hace falta que sean consecutivos. Por ejemplo:

1.Primer elemento

2.Segundo elemento

Sublistas:
1. Elemento principal
    1. Subelemento

Listas desordenadas

Se usan -, * o +. Por ejemplo:

Primer elemento

Segundo elemento

- Elemento principal
    * Subelemento

Párrafos

Para crear un párrafo nuevo basta con dejar una línea en blanco entre textos.

Bloques de código

Se pueden poner entre acentos graves simples si es una línea:
Todo esto es `código`.

Para varias líneas se usan tres acentos graves al inicio y al final:
<html>
  <head>
  </head>
</html>

Tablas
Se hacen con | y separando los encabezados con al menos tres guiones ---. Los dos puntos sirven para alinear las columnas.

Comandos de Git básicos en Markdown

git init  iniciar un repositorio

git add  añadir archivos

git commit -m  guardar los cambios

git push origin main  subir los cambios al repositorio de GitHub

HTML

Teoría de HTML
HTML (HyperText Markup Language) es el lenguaje que se usa para crear páginas web. Es el más importante de Internet porque sin HTML no se vería nada en el navegador. HTML define la estructura y el contenido de la web, como párrafos, títulos, listas, imágenes y enlaces. No sirve para dar estilo, que es lo que hace CSS, ni para hacer que la web interactúe, que se hace con JavaScript o PHP.

Los elementos HTML son los bloques de construcción de la web. Cada elemento tiene una etiqueta de apertura, contenido y etiqueta de cierre. Por ejemplo:
<p>Mi gato es muy gruñón</p>

Atributos
Los elementos pueden tener atributos, que añaden información extra sin alterar el contenido. Por ejemplo:
<p class="editor-note">Mi gato es muy gruñón</p>

Algunos elementos son vacíos, como <img> y no necesitan contenido. También se pueden anidar elementos dentro de otros.

Estructura básica de un fichero HTML
Una página HTML típica incluye:

Declaración <!DOCTYPE html>

Elemento <html> que contiene todo

Dentro de <html>, un <head> y un <body>

El <head> contiene metadatos, enlaces a hojas de estilo, scripts y otras cosas que no se ven directamente.
El <body> contiene todo lo visible de la página, como párrafos, listas, tablas, encabezados, imágenes y enlaces.
EJEMPLO:
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Mi página de prueba</title>
    <link rel="icon" href="favicon.png">
  </head>
  <body>
    <img src="imagenes/firefox-icon.png" alt="Mi imagen de prueba">
  </body>
</html>

Dentro del <body> hay elementos de bloque, que ocupan toda la línea y pueden contener otros elementos, y elementos en línea, que ocupan solo el espacio necesario y se usan dentro de otros elementos.

Actividad 1: Mi menú saludable
Hicimos una actividad llamada Mi menú saludable, donde el objetivo era crear una web mostrando cómo preparar un menú saludable con un primer plato, un segundo y un postre. La idea era poner en práctica todo lo aprendido y trabajar siguiendo la metodología de GitHub: primero en local y luego subir los cambios al repositorio remoto.

La web constaba de cuatro páginas: la principal y una página para cada plato. En la principal puse el título "Com preparar un menú saludable" y enlaces a las otras tres páginas, con imágenes de cada plato. Cada página de receta tenía favicon, un enlace para volver a la principal con un icono de flecha, un encabezado con el título del plato, un índice de contenidos con enlaces a ingredientes, pasos y resultado final, y cada sección estaba separada por líneas horizontales. En la sección de pasos, las cantidades se ponían en negrita y los ingredientes en texto normal, además de añadir imágenes para cada paso. Al final se incluía una imagen del resultado final y un enlace de vuelta al encabezado principal. Organicé las carpetas y los nombres de archivos de forma ordenada, validé todos los documentos HTML con el validador del W3C, publiqué la web en GitHub Pages y añadí la URL en la descripción del repositorio.



