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
2. Una vez que hayas seleccionado la tipografía, haz clic sobre ella para obtener el código necesario para incluir la fuente en tu sitio web.
3. Copia el código HTML estándar proporcionado por Google Fonts en la sección `<head>` de tu proyecto web. Debes pegarlo entre las etiquetas `<head>` y `</head>`. Por ejemplo:

```html
<head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap" rel="stylesheet">
</head>
```
4. Integra la fuente en tu código CSS en la hoja de estilos. Puedes aplicar la propiedad `font-family` para asignar la fuente a los elementos que desees. Por ejemplo:

```css
<style>
body {
  font-family: 'Roboto', sans-serif;
}
<style>
```
5. Guarda los cambios y refresca la página para ver cómo se ve la nueva tipografía aplicada en tu sitio web.

## Importación en CSS

También puedes añadir fuentes de Google Fonts utilizando la etiqueta `@import` en tu hoja de estilos CSS. Aquí te explico cómo hacerlo:

1. Inserta el código proporcionado por Google Fonts al principio de tu hoja de estilos CSS. Ejemplo de código:

```css
<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap');
   body {
     font-family: 'Roboto', sans-serif;
   }
<style>
```
2. Aplica la propiedad font-family en tu código CSS tal y como se ha especificado en Google Fonts.

## Uso en Wordpress
   
Es importante tener en cuenta que si modificas la fuente directamente en el tema de WordPress, perderás los cambios en la hoja de estilos si el tema se actualiza. Por lo tanto, se recomienda crear un tema hijo para hacer modificaciones personalizadas de la fuente.

Recuerda que Google Fonts es una herramienta útil para mejorar el diseño y la experiencia de usuario de tus páginas web, ya que ofrece una amplia variedad de tipografías de alta calidad y es fácil de usar y compatible con la mayoría de los navegadores y dispositivos.


