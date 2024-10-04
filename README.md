
## Indice ##

>[Tarea 1](#1-que-es-css)
>
>[Tarea 2](#2-colores-y-fuentes)
>
>[Tarea 3](#3-diseño-avanzado)
>
>[Tarea 4](#4-crear-una-tarjeta-de-presentacion-con-css-básico)
>
>[Tarea 5](#5-diferencias-entre-clases-e-identificadores-id-en-css)
>
>[Tarea 6](#6-uso-combinado-de-id-y-clases-en-css)

### 1 Que es CSS ###
[Que es CSS](./que_es_css)

>1. **¿Qué es CSS y para qué sirve?**  
>   - Busca en Internet qué es CSS (Cascading Style Sheets) y cuál es su función en el > >    desarrollo de páginas web.  
>   - Escribe una breve definición con tus palabras explicando para qué sirve y qué problemas soluciona.
>
>
>2. **Formas de aplicar CSS en HTML**  
>   - Investiga las diferentes formas de aplicar CSS a una página web. Debes describir y mostrar un ejemplo de cada una de estas:
>     - **CSS en línea (inline)**: Aplicando estilos directamente en el atributo de un elemento HTML.
>     - **CSS en el encabezado (internal)**: Usando la etiqueta `<style>` dentro de la cabecera del documento HTML.
>     - **CSS externo**: Vinculando un archivo CSS externo mediante la etiqueta `<link>` en la cabecera del HTML
>
>3. **Recursos de aprendizaje**  
>   - Busca en Internet páginas web y recursos que recomienden para aprender CSS de manera práctica. Algunos ejemplos pueden ser blogs, tutoriales o plataformas de aprendizaje.  
>   - Crea una lista de al menos 3 recursos confiables y explica brevemente por qué crees que pueden ser útiles.
>
>Objetivo:
>Este ejercicio te permitirá familiarizarte con CSS, aprender cómo aplicarlo en tus proyectos y descubrir recursos donde podrás seguir profundizando en este lenguaje de diseño.
>
>Crea un repositorio CSS en github y crea un fichero que_es_css.html, deberás ir a ajustes y pages para poder dar permisos para ver como página web


## 2 Colores y fuentes ##
[Colores y fuentes](./colores_y_fuentes.html)

>1. Crea un archivo HTML con varios párrafos y títulos (h1, h2, h3).
>
>2. Usa CSS para aplicar diferentes colores a los títulos y párrafos.
>
>3. Cambia la fuente y el tamaño de texto para cada tipo de título y párrafo.

## 3 Diseño avanzado ##
[Tarea 3](./padding.html)

>Explica para que sirven:
>
>“CSS margin”
>
>“CSS padding”
>
>“CSS border”
>
>“CSS width and height”
>
><img src="./padding.png">

## 4 Crear una tarjeta de presentacion con CSS básico ##
[Tarea 4](./tarjeta_de_presentacion.html)
>Instrucciones:
>
>1. Descripción del reto
>Vas a diseñar una tarjeta de presentación personal utilizando HTML y CSS. Tu objetivo es aprender a definir márgenes, relleno (padding), bordes y dimensiones, aplicando los estilos directamente en el archivo CSS.
>1. Requisitos del diseño
> - Contenido de la tarjeta:
>La tarjeta debe contener los siguientes elementos:
> - Tu nombre completo.
> - Tu profesión o título.
> - Una breve descripción sobre ti (2-3 frases).
> - Estilos de la tarjeta (con CSS):
>Investiga cómo aplicar los siguientes estilos y aplícalos a tu tarjeta:
> - Define un margen exterior para separar la tarjeta de los bordes de la pantalla.
> - Aplica relleno (padding) dentro de la tarjeta para que el texto no toque los bordes internos.
> - Añade un borde alrededor de la tarjeta con un grosor y color que elijas.
> - Define el ancho y alto de la tarjeta para que tenga un tamaño bien proporcionado (por ejemplo, 300px de ancho y 200px de alto).
> - Cambia el color de fondo de la tarjeta para darle estilo.
>
>1. Estructura básica del HTML
>Debes utilizar una estructura básica en HTML. Aquí te dejo un ejemplo inicial que puedes modificar:
>
>\<div class="tarjeta">
>
>  \<h2>Tu Nombre\</h2>
>
>  \<h3>Tu Profesión\</h3>
>
>  \<p>Descripción breve sobre ti.\</p>
>\</div>
>
>1. Vinculación con CSS
>Crea un archivo CSS separado y enlázalo a tu HTML para aplicar los estilos que investigues.
>1. Recursos
>Si no sabes por dónde empezar, busca en Internet términos como:
> - “CSS margin”
> - “CSS padding”
> - “CSS border”
> - “CSS width and height”

## 5 Diferencias entre clases e identificadores (ID) en CSS ##
[Tarea 5](./diferencias_de_clases.html)

>Instrucciones:
>
>
>1. Investiga:
>
>  - Busca en Internet las diferencias entre las clases (class) e identificadores (id) en CSS. En tu explicación, debes abordar:
>
>  - Cuándo es más adecuado usar una clase y cuándo un identificador.
>
>  - Cómo se utilizan en el HTML y cómo se referencian en el CSS.
>
>  - Las principales diferencias en cuanto a su uso y especificidad.
>
>1. Escribe una explicación:
>
>  - Redacta una explicación breve (máximo 5 frases) donde describas las diferencias y proporciona un ejemplo de cuándo utilizarías cada uno en una página web.

## 6 Uso combinado de ID y Clases en CSS ##
[Tarea 6](./uso_combinado.html)

>1.    Estructura HTML:
> - Crea una página HTML que contenga lo siguiente:
> - Un título (h1) con la clase titulo.
> - Dos párrafos con el mismo id llamado destacado (esto es incorrecto y no debería funcionar como esperas).
>-    Tres párrafos con la clase contenido.
>-    Un párrafo con tanto la clase contenido como el id especial.
>
>1.    Estilizar con CSS:
> - En tu archivo CSS, realiza lo siguiente:
> - Aplica un estilo general al título utilizando la clase titulo (por ejemplo, cambiar el tamaño y color de la fuente).
> - Aplica un color de fondo y un color de texto especial al párrafo con el id destacado.
> - Da un estilo común a los tres párrafos con la clase contenido (como color del texto y márgenes).
> - Sobrescribe el estilo del párrafo que tiene tanto la clase contenido como el id especial, aplicando un fondo diferente y un borde alrededor del párrafo.
>
>1. Desafíos adicionales:
> - Explica por qué no deberíamos repetir el id en varios elementos y qué sucede cuando lo hacemos.
> - Investiga cómo se comportan los navegadores cuando aplicas tanto un id como una clase en el mismo elemento. ¿Qué tiene más peso, el id o la clase? Usa tu párrafo con id y clase para comprobarlo.
