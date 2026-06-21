---
title: "HTML Básico"
autor: "José Juarez"
version: "01/06/26"
---


<!-- Image -->
   <center>![](){width=400px}</center>
   <center>
      <span class="grey3 size70"></span>
      <span class="grey3 size50"></span>
   </center>



<!-- *** GUIDE START *** -->


### Estructura de una página web

HTML significa **HyperText Markup Language** (Lenguaje de Marcado de Hipertexto). Es el lenguaje utilizado para indicar la estructura y el contenido de una página web.

Con HTML podemos agregar:

* Títulos
* Párrafos
* Imágenes
* Enlaces
* Tablas
* Formularios

HTML **no es un lenguaje de programación**, sino un lenguaje de marcado.

##### ¿Qué es una etiqueta?

Las páginas HTML están formadas por **etiquetas**.   

Ejemplos:

```html
<h1>Mi primera página</h1>

<p>Hola mundo</p>
```

- Las etiquetas suelen escribirse entre los símbolos `< >`.
- Las etiquetas con **"h"** vienen de *Heading*, que significa encabezado o título.
- Las que tienen **"p"** vienen de *Paragraph*, que en inglés significa párrafo

#### Etiqueta de apertura y cierre

Muchas etiquetas tienen:

~~~
<p>Contenido</p>
 |     |      |
 |     |      Etiqueta de cierre
 |     Contenido
 Etiqueta de apertura
~~~

Ejemplo:

```html
<p>Este es un párrafo.</p>
```

#### Actividad

Observa este [video](https://es.khanacademy.org/computing/computer-programming/html-css/intro-to-html/pt/html-basics). Luego abre block de notas y sigue estas instrucciones para hacer tu primer página web:

1. Abre el block de notas de Windows (Notepad) que es el editor más simple que tienes a disposición.
2. Abre tu documento de Word, el que hicisite en el pto. 3 de la guía de Ofimática. Usarás este para tu página web.
3. Copia el contenido que sugiere el video (figura de abajo) hasta llegar a la etiqueta `<title>` dentro de la sección `<head>`. Pon allí el título de tu documento word. Este es un metadato, algo que no aparece en la página misma pero sí en la pestaña del navegador.
4. A partir de la pestaña `<body>` empieza lo que verás en tu página realmente. Allí usa `<h1>` para poner de nuevo el título de tu texto, `<p>` para delimitar párrafos, `<h2>` para subtítulos o títulos de segundo nivel, etc.
5. Cuando llegues a la parte en donde haces una lista enumerando cosas tienes que estructurarlo con las pestañas `<ul>` (Unordered List → lista no ordenada) y `<li>` (List Item → elemento de lista) como se muestra abajo:

```html
<ul>
  <li>Manzana</li>
  <li>Banana</li>
</ul>
```

6. Por ahora no vamos a incluir la tabla de tu texto por lo que luego de lo anterior guardas con el nombre *mi_pagina.html* y lo abres con el navegador (puede ponerle otro nombre pero siempre termina con `.html`. Puedes ver como quedó la página web del ejemplo dado en ofimática [aquí](html-1-solved.html).

<!-- Image -->
<br>
   <center>![](web/html_estructura.png){width=400px}</center>
   <center>
      <span class="grey3 size70">Ejemplo de una página. </span>
      <span class="grey3 size50">Fuente: khanacademy.org</span>
   </center>
<br>

**Aclaración:** En HTML la "sangría" (indentación) no cambia cómo funciona la página, pero sirve para que el código sea más ordenado y fácil de leer. 

> Esta actividad se aprueba mostrando y explicando al profesor

<!-- *** GUIDE END *** -->


<!-- *** GUIDE AUXILIARY TEMPLATES *** -->


<div hidden>


<!-- Learning objectives very briefly -->
<span class="grey3 size85">.</span>

<!-- Image -->
<br>
   <center>![](){width=400px}</center>
   <center>
      <span class="grey3 size70">. </span>
      <span class="grey3 size50">Fuente: </span>
   </center>
<br>

<!-- Videos: change XXX to the video-id and put time (seconds) -->
<!-- Yotube with start point -->
👉 [Mira este momento clave en el video](https://www.youtube.com/watch?v=XXX&t=123s)
🎬 [Un fragmento que vale la pena ver](https://www.youtube.com/watch?v=XXX&t=123s)
🔎 [Este detalle del video te va a interesar](https://www.youtube.com/watch?v=XXX&t=123s)
⚡ [Dale play a esta parte y fijate qué pasa](https://www.youtube.com/watch?v=XXX&t=123s)
<!-- Youtubetrimmer with start and end point -->
👉 [Mirá este momento puntual del video](https://youtubetrimmer.com/view/?v=XXX&start=120&end=150&loop=0)
🎬 [Este fragmento explica justo lo que necesitamos](https://youtubetrimmer.com/view/?v=XXX&start=120&end=150&loop=0)
⚡ [Dale play a esta parte y sacá tus conclusiones](https://youtubetrimmer.com/view/?v=XXX&start=120&end=150&loop=0)
🔎 [Fijate qué pasa en este momento](https://youtubetrimmer.com/view/?v=XXX&start=120&end=150&loop=0)

<!-- Visible story or anecdote -->
<span class="grey3 size85">...</span>

<!-- Sections -->
<br><span class="grey3 size70">🔁 Repaso:</span>
<br><span class="grey3 size70">🛠️ Trabajo:</span>
<br><span class="grey3 size70">📘 Teoría:</span>
<br><span class="grey3 size70">✅ Autoevaluación:</span>
<br><span class="grey3 size70">📝 Práctica:</span>
**1.**  **:**
**2.** **:** 

<!-- Solutions -->
<div class="grey3 size70">.</div>


</div>


<!-- Guide style definitions -->
<style>
/* Colors */
.grey1 {color: #b3b3b3;} /* my light-grey */
.grey2 {color: #999999;} /* my middle-grey */
.grey3 {color: #808080;} /* my dark-grey */
.blue1 {color: #6495ed;} /* nvim blue */
.blue2 {color: #276cdf;} /* Andrew Ng Blue */
.sky1 {color: #7dbed8;} /* nvim sky */
.sky2 {color: #27a2db;}   /* my sky */
.green {color: #81b524;} /* my green */
.red1 {color: #ec5469;} /* my coral-red */
.red2 {color: #f44336;} /* my red */
.rose {color: #ec9998:} /* nvim rose */
.gold {color: #df9d43;} /* Andrew Ng gold */
.orange1 {color: #fda556;} /* nvim orange */
.orange2 {color: #ff9505;} /* Andrew Ng orange */
.purple1 {color: #ff40ff;} /* Andrew Ng purple */
.purple2 {color: #d164d7;} /* Andrew Ng purple */
/* Font Size */
.size90 {font-size: 0.9em;}
.size85 {font-size: 0.85em;}
.size80 {font-size: 0.8em;}
.size70 {font-size: 0.7em;}
.size60 {font-size: 0.6em;}
.size50 {font-size: 0.5em;}
/* Document General Font Size */
body {font-size: 1.3em;}
/* Bullet "1." see as "1)" */
ol {list-style-type: decimal;}
ol li::marker {content: counter(list-item) ") ";}
/* Two columns */
.two-columns {
  column-count: 2; /* Number of columns */
  column-gap: 20px;
}
/* Indent the example */
.example {margin-left: 20px;}

/* =========================
   IMPRESIÓN A4 – GUÍAS
   ========================= */
@media print {

  @page {
    size: A4;
    margin: 1.2cm;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 10.5pt;
    line-height: 1.35;
    color: #000;

    column-fill: auto; /* Llena una columna y después la otra*/
    column-count: 2;
    column-gap: 1cm;
  }

  h1 {
    font-size: 14pt;
    margin: 0 0 6pt 0;
  }

  h2 {
    font-size: 12pt;
    margin: 8pt 0 4pt 0;
  }

  h3 {
    font-size: 11pt;
    margin: 6pt 0 3pt 0;
  }

  h1, h2, h3 {
    break-after: avoid;
    break-inside: avoid;
  }

  p {
    margin: 0 0 4pt 0;
    text-align: justify;
    break-inside: avoid;
  }

  ul, ol {
    margin: 0 0 4pt 12pt;
    padding: 0;
  }

  li {
    margin-bottom: 2pt;
  }

  code, pre {
    font-family: "Courier New", Courier, monospace;
    font-size: 9.5pt;
    background: #f2f2f2;
    padding: 1px 3px;
    border-radius: 2px;
  }

  pre {
    padding: 6pt;
    overflow: hidden;
    break-inside: avoid;
  }

  img {
    max-width: 100%;
    height: auto;
    break-inside: avoid;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    font-size: 9.5pt;
  }

  th, td {
    border: 1px solid #000;
    padding: 3pt;
  }

  nav, footer, .no-print {
    display: none;
  }
}
</style>
<!-- Remember: Use <span> inline and <div> with several lines --->
