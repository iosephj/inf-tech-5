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


### 1. Estructura básica de una página HTML (Repaso)

Toda página HTML suele comenzar así:

```html
<!DOCTYPE html>
<html>

<head>
    <title>Mi primera página</title>
</head>

<body>
    <h1>Hola mundo</h1>
    <p>Mi primera página web.</p>
</body>

</html>
```

- `<!DOCTYPE html>` Indica que el documento utiliza HTML5.
- `<html>` Contiene toda la página.
- `<head>` Contiene información para el navegador: Título de la pestaña, Configuración, Enlaces a archivos CSS.
- `<title>` Define el texto que aparece en la pestaña del navegador. Este no se ve en la página.
- `<body>` Contiene todo lo que verá el usuario. Ejemplos: Textos, Imágenes, Tablas, Botones
- `<h1>` Título principal. Existen niveles desde `h1` hasta `h6`.
- `<p>` Párrafo

<br>

### 2. Saltos de línea

Un salto de línea es un cambio de renglón. El navegador cambia de renglón en un texto solo cuando ve `<br>`.

```html
Primera línea<br>
Segunda línea
```

<br>

### 3. Línea horizontal

Pueden usarse para separar partes. Se insertan con `<hr>`


```html
<hr>
```

<br>

### 4. Inserción de imágenes 

Para insertar una imagen en HTML se usa la etiqueta `<img>`. Es una etiqueta "autocerrante", lo que significa que no necesita una etiqueta de cierre (no lleva `</img>`).

Acá tenés la estructura básica y más usada:

```html
<img src="imagen.png" alt="Descripción de la imagen">

```

##### Los dos atributos que lleva sí o sí:

* **`src` (source/origen):** Indica **dónde está** el archivo de la imagen. Puede ser el nombre de un archivo que tengas en la misma carpeta (como `foto.jpg`) o una dirección web (URL) completa.
* **`alt` (texto alternativo):** Es una **descripción corta** de la imagen. No se ve en la pantalla, pero es fundamental por dos razones: si la imagen no carga por problemas de internet, aparece ese texto en su lugar; y además, es lo que leen los sistemas de asistencia para personas con discapacidad visual.


##### Ejemplo práctico en código:

En este primer ejemplo luego de `src=` se pone la dirección web de una imagen, pregunta al profesor como se obtiene si no lo sabes.

```html
<img src="https://ejemplo.com/paisaje.jpg" alt="Montaña con nieve durante el amanecer">
```

En este segundo ejemplo luego de `src=` se pone el nombre de un archivo guardado en el disco rígido en la misma carpeta donde está el archivo html.

```
<img src="mi-moto.jpg" alt="Mi motocicleta estacionada de perfil">

```

##### Actividad

Abre el block de notas y haz una página con un título, lineas y al menos dos imágenes. Una de las imágenes tiene que ser una imagen que esté en la web. Laa otra imagen hazla con paint, algo sencillo, y muestralo en tu página web. Es decir una imagen está en la nube y la otra está en tu computadora. 

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
