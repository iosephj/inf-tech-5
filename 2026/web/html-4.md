---
title: "HTML Básico (4): Hacer tablas en HTML"
autor: "José Juarez"
version: "19/10/26"
---

<!-- *** GUIDE START *** -->

Para crear una tabla básica en HTML, se utilizan las siguientes etiquetas principales:

* `<table>`: Define la tabla en sí.
* `<tr>`: Define una fila (*table row*).
* `<th>`: Define una celda de encabezado (*table header*), que suele ir en negrita y centrada.
* `<td>`: Define una celda de datos normal (*table data*).
 
Puedes ver una explicación en este [video](https://es.khanacademy.org/computing/computer-programming/html-css/html-tags-continued/pt/html-tables)

### Ejemplo de código

```html
<table border="1">
  <tr>
    <th>Nombre</th>
    <th>Edad</th>
    <th>Ciudad</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
    <td>Madrid</td>
  </tr>
  <tr>
    <td>Carlos</td>
    <td>30</td>
    <td>Buenos Aires</td>
  </tr>
</table>

```

### Consejo adicional

El atributo `border="1"` es solo para visualizar las líneas de guía básicas. Para un diseño moderno, es mejor utilizar **CSS** para los bordes y el espaciado (propiedades como `border-collapse`, `padding`, etc.).

### Actividad

::: activity

- Busca en la web un editor html, pega tu código allí, verás que puedes ver las cosas de un modo más visual que el block de notas. Por ejemplo puedes usar [HCODX](https://hcodx.io/editor/) del siguiente modo: 

   + Abres el link
   + Eliges Open files (Abrir archivos)
   + Seleccionas el archivo html y el de la imagen
   + Hay una opción llamada "Split View" que permite ver el código y la apariencia al mismo tiempo.

- Agrega una tabla en tu página

:::

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
