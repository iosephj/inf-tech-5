---
title: "HTML Básico (5): Mejorar el diseño"
autor: "José Juarez"
version: "19/10/26"
---

<!-- *** GUIDE START *** -->


## 1. Cambiar las tipografías

CSS permite cambiar el tipo, tamaño, grosor y alineación de los textos.

**Tipo de letra (`font-family`)**

```
body {
    font-family: Arial, sans-serif;
}
```

Algunas alternativas:

```
font-family: Arial, sans-serif;
font-family: Georgia, serif;
font-family: Verdana, sans-serif;
font-family: "Courier New", monospace;
font-family: "Times New Roman", serif;
font-family: Tahoma, sans-serif;
```

**Tamaño (`font-size`)**

```
h1 {
    font-size: 36px;
}

p {
    font-size: 18px;
}
```

**Grosor (`font-weight`)**

```
h1 {
    font-weight: bold;
}

p {
    font-weight: normal;
}
```

**Alineación (`text-align`)**

```
h1 {
    text-align: center;
}

p {
    text-align: justify;
}
```

### Actividad

::: activity

Probá diferentes tipos de letra en tu página. Elegí uno para los títulos y otro para los párrafos. Modificá también sus tamaños y alineaciones. Esto se hace en la parte del CSS.

:::


## 2. Adaptar la página a pantallas pequeñas

Una página web debe verse correctamente tanto en una computadora como en un celular. Para eso vamos a realizar tres modificaciones.

**Paso 1. Configurar el HTML**

Dentro de `<head>`, agregá esta línea:

```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Esta instrucción le indica al navegador que debe adaptar el ancho de la página al ancho real de la pantalla del dispositivo. Sin ella, la página podría mostrarse demasiado grande en un celular.

**Paso 2. Adaptar las imágenes**

En CSS, agregá:

```
img {
    max-width: 100%;
    height: auto;
}
```

Así las imágenes no superarán el ancho disponible y conservarán sus proporciones.

**Paso 3. Modificar el diseño para pantallas pequeñas**

Agregá al final de tu CSS:

```
@media (max-width: 600px) {
    h1 {
        font-size: 24px;
    }

    body {
        font-size: 16px;
    }
}
```

`@media` permite aplicar estilos solamente cuando se cumple una condición. En este caso, las reglas se aplican cuando el ancho de la pantalla es de 600 píxeles o menos.

### Actividad

::: activity

**a)** Realizá los tres pasos anteriores.

**b)** Achicá la ventana del navegador hasta simular la pantalla de un celular. Observá cómo cambian las imágenes y los textos.

:::

>Para aprobar esta guía debes mostrar y explicar bevemente esto al profesor

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
