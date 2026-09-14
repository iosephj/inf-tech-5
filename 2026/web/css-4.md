---
title: "CSS Básico (4): Repaso de selectores básicos"
autor: "José Juarez"
version: "24/08/26"
---

<!-- *** GUIDE START *** -->
## Repaso

Los selectores CSS permiten elegir qué elementos HTML modificar: por etiqueta (`p`), por clase (`.destacado`) o por ID (`#titulo`).

::: example

**Ejemplo:**

Aquí se muestra como los selecciono y pongo propiedades dentro de CSS: 

```css
/* Por etiqueta */
p {
    color: blue;
}

/* Por clase */
.destacado {
    color: red;
}

/* Por ID */
#titulo {
    font-size: 30px;
}
```

Aquí se muestra como aparecen dentro del html:


```html
<h1 id="titulo">Mi título</h1>

<p class="destacado">Texto importante</p>
<p>Texto normal</p>
```
:::

**Resumen:**

* **Etiqueta** → `p` → selecciona todos los `<p>`.
* **Clase** → `.destacado` → puede aplicarse a **muchos elementos**.
* **ID** → `#titulo` → identifica normalmente **un elemento único**.

### Actividad

::: activity

Abre este [link](https://es.khanacademy.org/computing/computer-programming/html-css/intro-to-css/e/quiz--simple-css-selectors) de Khan Academy y realiza los ejercicios interactivos de repaso que allí se proponen (son 4). 

:::

> Para aprobar esta guía debes hacer los ejercicios de Khan Academy y explicar en forma oral la diferencia entre usar una clase y un id. 

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
