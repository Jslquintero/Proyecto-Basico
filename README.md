# Documentación HTML Básica

Documentacion de HTML y CSS basico para el curso de Desarrollo Web de BoluTech

# Estructura de carpetas para HTML básico con CSS y JS

Esto es una estrucutra Generica, puede variar dependiendo de la necesidad del proyecto

    * assets
        * css
            * styles.css
            * _estilosIndividuales.css
        * img
            * logo.png/svg/jpg
            * imagenes individuales
    * scripts
        * scripts.js
    * views    
        * _vistasIndividuales.html
     * index.html
## Etiquetas

- `<!DOCTYPE html>`: Define la versión de HTML utilizada en el documento.
- `<html>`: La etiqueta raíz que envuelve todo el contenido del documento.
- `<head>`: Contiene metadatos e información del documento, incluyendo las etiquetas `meta` y `link`.
- `<meta charset="UTF-8">`: Define la codificación de caracteres del documento.
- `<meta http-equiv="X-UA-Compatible" content="IE=edge">`: Indica al navegador que use la última versión de Internet Explorer disponible.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Define la escala de la página web para adaptarse a diferentes tamaños de pantalla.
- `<link rel="stylesheet" href="./assets/css/styles.css">`: Vincula una hoja de estilos externa al documento.
- `<title>`: Define el título del documento que aparece en la pestaña del navegador.
- `<body>`: Contiene el contenido visible del documento.
- `<h1>`: Encabezado de nivel 1 que indica el título principal de la sección.
- `<form>`: Crea un formulario que se enviará al servidor cuando el usuario haga clic en el botón de enviar.
- `<input>`: Crea un campo de entrada de datos en el formulario.
- `class`: Atributo de la etiqueta que asigna una o varias clases a la etiqueta para aplicar estilos CSS.
- `id`: Atributo de la etiqueta que asigna un identificador único a la etiqueta para seleccionarla desde JavaScript o CSS.
- `type`: Atributo de la etiqueta `input` que define el tipo de entrada de datos.
- `name`: Atributo de la etiqueta `input` que define el nombre del campo de entrada.
- `placeholder`: Atributo de la etiqueta `input` que define el texto de marcador de posición que aparece en el campo de entrada.
- `for`: Atributo de la etiqueta `label` que define la identificación del campo de entrada asociado al texto de la etiqueta.
- `action`: Atributo de la etiqueta `form` que define la URL del servidor donde se enviarán los datos del formulario.
- `<button>`: Crea un botón que se puede hacer clic para enviar el formulario.
- `div`: Crea una división o sección en el documento.


## Estilos

- `background-color`: Define el color de fondo de un elemento.
- `color`: Define el color del texto de un elemento.
- `display`: Define el tipo de visualización de un elemento.
- `font-family`: Define la familia de fuentes de un elemento.
- `font-size`: Define el tamaño de la fuente de un elemento.
- `font-weight`: Define el grosor de la fuente de un elemento.
- `height`: Define la altura de un elemento.
- `margin`: Define el margen de un elemento.
- `padding`: Define el relleno de un elemento.
- `text-align`: Define la alineación del texto de un elemento.
- `width`: Define el ancho de un elemento.
- `border`: Define el borde de un elemento.
- `border-radius`: Define el radio de las esquinas del borde de un elemento.
- `box-shadow`: Define la sombra de un elemento.
- `cursor`: Define el tipo de cursor que se muestra cuando el ratón se coloca sobre un elemento.
- `flex`: Define la propiedad flex de un elemento.
- `flex-direction`: Define la dirección de los elementos flexibles de un elemento.
- `justify-content`: Define la alineación de los elementos flexibles de un elemento.
- `align-items`: Define la alineación de los elementos flexibles de un elemento.
- `position`: Define la posición de un elemento.

## ¿Por qué los estilos estan dividios y otros están en el mismo html?

- Los estilos que están en el mismo html son estilos que se utilizan una sola vez, por ejemplo, el color de un texto o el tamaño de una fuente.
- Los estilos que están en el archivo styles.css son estilos que se utilizan varias veces, por ejemplo, el color de fondo de un botón o el tamaño de una imagen.
- En este proyecto de ambas formas, pero en proyectos reales se recomienda utilizar el archivo styles.css para los estilos que se utilizan varias veces.
- Es importante tener en cuenta que los estilos que están en el archivo styles.css tienen prioridad sobre los estilos que están en el mismo html.
- Los estilos han sido importados en el archivo styles.css para que se puedan utilizar en el proyecto de forma global y no tener que importarlos en cada archivo html, pero también se pueden importar en cada archivo html si se es necesario.
- Utilizando @import se pueden importar estilos de otros archivos css, por ejemplo, `@import url('./_estilosIndividuales.css');` al directorio de estilos generales
- Siempre trata de tener nombres que sean descriptivos para los estilos, por ejemplo, `btn-primary` para un botón primario, `btn-secondary` para un botón secundario, etc.
- Si te sientes aglomerada con los estilos puedes dividrlos por regiones con la siguiente notacion `/* region: nombre */` y `/* end-region */` para cerrar la region.


## Tarea

- Culminar el formulario `Contácto` y hacer un `footer(pie de pagina)` con los datos de la empresa.
- Optimizar las clases que se repiten, por ejemplo ` margin-top: 0.5rem;` se repite en varias clases, se puede crear una clase que se llame `mt-05` y que tenga ese estilo.


## Observaciones

- No es necesario que la pagina sea responsive aun, el uso de flex fue solo para mover elementos necesarios.
- El nombre de clases y estilos pueden ser en espanol, pero en ingles es mas generico y se puede reutilizar en otros proyectos.