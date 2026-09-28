---
title: "HTML Básico (3): Hacer links o vínculos"
autor: "José Juarez"
version: "28/09/26"
---

<!-- *** GUIDE START *** -->

## 1. Repaso y contexto

**HTML** significa *HyperText Markup Language*. iteralmente significa “Lenguaje de Marcado de Hipertexto”, pero se puede entender mejor como un lenguaje en el que marcamos mediante etiquetas distintas características de un texto y podemos conectarlo con otros textos.

**Hyper** indica que algo permite ir más allá... en este contexto indica que podemos ir de un contenido a otro, saltando de un texto a otro mediante vínculos.

Una **URL** es la dirección de un recurso en Internet. Por ejemplo:

```text
https://www.ejemplo.com/carpeta/pagina.html
```

* `https://` → **protocolo**, indica cómo se comunica el navegador con el sitio.
* `www.ejemplo.com` → **dominio**, identifica el sitio.
* `/carpeta/pagina.html` → **ubicación**, indica dónde se encuentra el recurso dentro del sitio.

## 2. Hacer un vínculo externo

Puedes ver este contenido también en este [video](https://es.khanacademy.org/computing/computer-programming/html-css/html-tags-continued/pt/html-links).

Para enlazar una página de otro sitio se utiliza `<a>` (de "ancla") indicando la URL completa:

```html
<a href="https://www.google.com">Google</a>
         ----------------------  ------ 
                  url             texto                                  
```

La url no es visible pero lo que pones como texto si lo es. 

Si quieres abrirlo en otra pestaña del navegador usas "target" como se muestra abajo:

::: example

```html
<a href="https://www.google.com" target="_blank">Google</a>
```

:::

Esto hace que el vínculo se abra en **otra pestaña** del navegador.


## 3. Vínculo interno dentro de la misma página

Puedes querer por ejemplo en algún lugar de la página ir a la sección donde están los datos de contacto: dirección, teléfono, etc.

Para esto se usa también la etiqueta `<a>` con el `id` de lugar específico donde están los datos de contacto:

Por ejemplo:

::: example

```html
<a href="#contacto">Ir a Contacto</a>
         ---------  -------------
            id      texto visible
```

El `#contacto` indica que el navegador debe desplazarse hasta el elemento que tiene `id="contacto"`.

Luego en el lugar de tu página donde están los datos de contacto, precisamente en el título de esa parte, pones:

```html
<h2 id="contacto">Contacto</h2>
        --------
           id
```

:::


## 4. Actividad

Agregá en la página que estás haciendo:

**a)** Al menos **un vínculo externo** hacia otra página web.

**b)** Al menos **un vínculo interno** hacia otra parte de tu sitio.

> Para aprobar esta guía debes mostrar y explicar bevemente esto al profesor

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
