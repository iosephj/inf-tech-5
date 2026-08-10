---
title: "CSS Básico (2)"
autor: "José Juarez"
version: "10/08/26"
---

<!-- *** GUIDE START *** -->


## Identificar elementos con `id`

Hasta ahora usamos CSS para modificar elementos de la página, por ejemplo:

```css
h1 {
    color: blue;
}
```

Esto modifica todos los `<h1>`.

Pero ¿qué pasa si queremos modificar **un elemento particular**?

### `id`

Podemos darle un nombre a un elemento HTML:

```html
<h1 id="titulo">Mi tema</h1>
```

Y utilizar ese nombre en CSS colocando `#` delante:

```css
#titulo {
    color: red;
    background-color: yellow;
}
```

El `id` identifica **un elemento particular** de la página.

Puedes repasar esta lección con este [video explicativo](https://es.khanacademy.org/computing/computer-programming/html-css/intro-to-css/pt/css-selecting-by-id).

### Actividad

::: activity

Trabajá sobre la página que estás construyendo.

**1.**  Destacá una parte importante. Elegí un elemento que quieras destacar: puede ser el título, un subtítulo, un párrafo, una imagen, etc. Asignale un `id` y modificá su apariencia con CSS.

::: example

Por ejemplo:

```html
<h2 id="historia">Historia</h2>
```

Luego en dentro de style pones la regla css empezando con "#":

```css
#historia {
    color: color: rgb(139, 0, 0); /* rojo oscuro */
}
```
:::

Probá diferentes propiedades y valores.

**2)** Mejorá una imagen

Elegí una de las imágenes de tu página y asignale un `id`:

```html
<img id="imagen-principal" src="mi-imagen.jpg">
```

Luego podés modificarla desde CSS:

```css
#imagen-principal {
    width: 400px; /* ancho en pixeles */
    border: 3px solid black; /* borde sólido negro de 3 pixeles */
}
```

`width` cambia el ancho de la imagen y `border` agrega un borde.

**Probá cambiar los valores y observá qué sucede.**

Después, intentá modificar la imagen de otra manera que te parezca interesante.


**3)** Destacá una información: Buscá dentro de tu texto una información que consideres especialmente importante. Dale un `id` y creá un estilo que permita distinguirla del resto del texto. Por ejemplo pon el mismo color de fondo a uno de los párrafos y al subtítulo.

:::

> Para aprobar esta guía debes mostrar las actividades y explicarlas.

<!-- *** GUIDE END *** -->



<!-- *** GUIDE AUXILIARY THINGS *** -->

<!--

● Sections: example, activity. solutions, figure, warning, note

::: example
### Ejemplo: Cálculo de derivadas
Aquí va el contenido de tu ejemplo. Puedes usar Markdown normal adentro.
:::


● Image:

::: figure
![](imagen.png){width=400px}

<small>Pie (Source)</small>
:::

[⌕](../../images/ ) 

● Videos:

 Change XXX to video-id and put time in seconds

 - Yotube with start point: [Mira este momento clave en el video](https://www.youtube.com/watch?v=XXX&t=123s)

 - Youtubetrimmer with start and end point: [Mirá este momento puntual del video](https://youtubetrimmer.com/view/?v=XXX&start=120&end=150&loop=0)

-->
