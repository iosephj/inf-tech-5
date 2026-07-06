---
title: "CSS Básico (1)"
autor: "José Juarez"
version: "01/06/26"
---

<!-- *** GUIDE START *** -->


## Dar color al texto y al fondo de una página

Hasta ahora conseguimos armar una página básica con texto e imágenes.  Vamos empezar a darle un estilo más personal. Empecemos con el texto y con el color de fondo para lo cual:

- Para los títulos `h1`, `h2` y el resto del texto del documento que está dentro de `body` usamos la propiedad `color`.
- Para el color de fondo de la página, es decir todo lo que está dentro de `body` usamos la propiedad `background-color`.
- Para asignar el color vamos a usar el sistema rgb que conciste en combinar tres números que indican intensidad. El primero para `r` (red), el segundo `g` (green) y el tercero para `b` (blue). Estos números van del 0 al 255 y de su combinación salen múltiples colores.

::: example

### Ejemplo

```CSS
<style>
    h1 {
        color: rgb(31, 78, 121); /* azul acero */
    }
</style>
```

Aquí:

- el código CSS va dentro de un bloque `<style>` que a su vez va dentro del bloque `<head>` del html.
- en CSS, lo que va entre `/*` y `*/` es un comentario aclaratorio no obligatorio

:::



::: activity

### Actividad

Siguiendo esta actividad paso a paso modificarás colores en tu página web: 

**1)** Este [video](https://www.youtube.com/embed/dC34rfY8Eyk) explica brevemente lo que queremos hacer. Si quieres míralo.

**2)** **Definir colores:** Para ver colores en rgb se pueden experimentar con varias páginas que permiten poner números y muestra el color. Por ejemplo puedes experimentar con [ésta](https://htmlcolorcodes.com/es/).

**3)** **Crear código CSS:** Se agrega dentro de las etiquetas `<style>   </style>` que se ubican dentro de `<head>  </head>`. Luego especificas los colores para h1, h2 y el body. Recuerda que dentro del `body` está todo lo que aparece en la página. 

   + [Aquí](../../images/web/css-1-solved.png) puedes verr como queda el código para mi página.
   + [Aquí](css-1-solved.html) puedes ver como queda si lo abres en el navegador.

**4)** **Investiga** como poner un subrayado a un título en CSS y subraya el título `h1` 

:::

> Esta actividad se aprueba mostrando y explicando al profesor


<!-- *** GUIDE END *** -->


<!-- *** GUIDE AUXILIARY THINGS *** -->

<!--

● Sections: example, activity. soluciones, figure, warning, note

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
