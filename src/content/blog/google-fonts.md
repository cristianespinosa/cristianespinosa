---
author: Cristian Espinosa
pubDatetime: 2023-06-27T10:30:00.737Z
title: Potencia el diseño de tus proyectos web con Google Fonts
postSlug: como-usar-google-fonts
featured: true
ogImage: "/assets/images/google-fonts.webp"
tags:
  - desarrollo web
  - google fonts
description: Cómo usar google fonts en tus proyectos web.
draft: false
---

Como programador web, puedes usar Google Fonts para añadir las tipografías personalizadas a tus proyectos web, cómo páginas y aplicaciones web. Aquí te explico cómo hacerlo:

![Desarrollo Web](/assets/images/google-fonts.webp)

1. Elige la tipografía que deseas utilizar en tu sitio web. Puedes buscar y explorar diferentes opciones en [Google Fonts](https://fonts.google.com/).
2. Una vez que hayas seleccionado la tipografía, haz clic en **"Quick Use"** para obtener el código necesario para incluir la fuente en tu sitio web.
3. Copia el código HTML estándar proporcionado por Google Fonts en la sección `<head>` de tu proyecto web. Debes pegarlo entre las etiquetas `<head>` y `</head>`. Por ejemplo:

```html
<head>
  <link rel="stylesheet" type="text/css" href="https://fonts.googleapis.com/css?family=Open+Sans">
</head>
```
4. Integra la fuente en tu código CSS en la hoja de estilos. Puedes aplicar la propiedad `font-family` para asignar la fuente a los elementos que desees. Por ejemplo:

```css
<style>
body {
  font-family: 'Open Sans', sans-serif;
}
<style>
```
5. Guarda los cambios y refresca la página para ver cómo se ve la nueva tipografía aplicada en tu sitio web.
   
Es importante tener en cuenta que si modificas la fuente directamente en el tema de WordPress, perderás los cambios en la hoja de estilos si el tema se actualiza. Por lo tanto, se recomienda crear un tema hijo para hacer modificaciones personalizadas.
