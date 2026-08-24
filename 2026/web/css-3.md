---
title: "CSS Básico (3): Clases"
autor: "José Juarez"
version: "24/08/26"
---

<!-- *** GUIDE START *** -->

## Introducción

Hasta ahora usamos `id` para identificar un elemento particular.

Por ejemplo:

```html
<h1 id="titulo">Mi tema</h1>
```

Una **clase (`class`)** permite agrupar varios elementos que queremos diseñar de la misma manera.

## ¿Cómo se utiliza?

Supongamos que tenemos varios párrafos en nuestro HTML. La clase `class` se agrega justo luego de `<p`:

```html
<p class="texto">Primer párrafo.</p>
<p class="texto">Segundo párrafo.</p>
```

Luego en CSS, es decir dentro de `<style>`, se selecciona la clase utilizando un punto `.` y luego asignando las propiedades tal como venimos haciendo:

```css
.texto {
    color: rgb(60, 60, 60);
    font-family: Arial;
}
```

Los dos párrafos tendrán el mismo estilo.

> **Recordá:**
>
> `#nombre` → `id`
> `.nombre` → `class`

Puedes repasar esta lección con este [video](https://www.youtube.com/embed/xiGguPT09sQ).

## Actividades

::: activity

**1)** Continuá trabajando sobre la página que ya venís construyendo:

- *a.* Agrega dos o más párrafos nuevos en el html.
- *b.* Asigna la misma clase a **todos los párrafos** de tu página:

```html
<p class="texto">Primer párrafo...</p>

<p class="texto">Segundo párrafo...</p>

<p class="texto">Nuevo párrafo...</p>
```

- *c.* Luego diseñalos desde CSS:

```css
.texto {
    color: rgb(60, 60, 60);
    font-family: Arial;
    font-size: 18px;
}
```

- *d.* Los valores anteriores son de ejemplos, puedes elegir un estilo diferente que combine con el tema y el diseño de tu página. **La idea es que todos los párrafos tengan un aspecto coherente.**

**2)** **Profundización:** Creá una segunda clase para destacar una información importante de tu página.

Por ejemplo:

```html
<p class="destacado">
    Esta información es especialmente importante.
</p>
```

Creá el estilo en CSS y decidí qué características debería tener un texto destacado.

Probá distintas propiedades y valores hasta encontrar un diseño que te guste.

**3)** **Desafío:** Ahora combiná las clases con los `id` que aprendiste anteriormente para dar una mejor armonía y estilo a tu página. Usá:

* una `class` para aplicar un estilo común a varios elementos;
* un `id` para darle un estilo particular a un elemento.

El objetivo es que **el diseño tenga una intención**: organizar la información, destacar algo importante o facilitar la lectura.

Recuerda como se usa cada uno:

```text
id → identifica un elemento particular
class → permite agrupar elementos con un mismo estilo
```

```css
#titulo {
    color: rgb(139, 0, 0);
}

.texto {
    color: rgb(60, 60, 60);
}
```
:::


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
