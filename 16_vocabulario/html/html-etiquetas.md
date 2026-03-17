# Vocabulario HTML

---

## html 000001

**Tipo:** etiqueta raíz  
**Función:** define el inicio y fin de un documento HTML  

**Descripción:**

Es la etiqueta principal de toda página web.  
Todo el contenido debe estar dentro de esta etiqueta.

Sin esta etiqueta, el navegador no reconoce correctamente el documento como una página HTML.

**Ejemplo:**

<html>
    <head>
        <title>Mi página</title>
    </head>

    <body>
        <h1>Hola mundo</h1>
    </body>
</html>

---

## head  000002

**Tipo:** etiqueta  
**Función:** contiene información de configuración de la página  

**Descripción:**

La etiqueta <head> no muestra contenido visible en la página.

Se utiliza para definir información importante para el navegador, como:

- el título de la página  
- la conexión con archivos CSS  
- metadatos (configuración interna)  

Es una parte esencial para que la página funcione correctamente.

**Ejemplo:**

<head>
    <title>Mi página</title>
    <link rel="stylesheet" href="style.css">
</head>

---

## title 000003

**Tipo:** etiqueta  
**Función:** define el título de la página en el navegador  

**Descripción:**

La etiqueta <title> se utiliza dentro del <head> y define el nombre que aparece en la pestaña del navegador.

No es contenido visible dentro de la página, pero es importante porque:

- identifica la página  
- mejora la organización en el navegador  
- ayuda en buscadores (SEO básico)  

**Ejemplo:**

<head>
    <title>Mi primera página</title>
</head>

---

## link 000004

**Tipo:** etiqueta  
**Función:** conectar recursos externos al HTML (como archivos CSS)  

**Descripción:**

La etiqueta <link> se utiliza dentro del <head> para enlazar archivos externos al documento HTML.

Su uso más común es conectar un archivo CSS para aplicar estilos a la página.

Es una etiqueta especial porque:

- no tiene etiqueta de cierre  
- funciona como conexión externa  
- no muestra contenido visual directamente  

**Atributos importantes:**

- rel → define la relación (ej: stylesheet)  
- href → indica la ruta del archivo  

**Ejemplo:**

<head>
    <link rel="stylesheet" href="style.css">
</head>

---

## body 000005

**Tipo:** etiqueta  
**Función:** contiene todo el contenido visible de la página  

**Descripción:**

La etiqueta <body> contiene todo lo que el usuario puede ver en la página web.

Dentro de esta etiqueta se colocan elementos como:

- textos  
- títulos  
- imágenes  
- botones  
- listas  
- secciones  

Todo lo que aparece en pantalla está dentro del <body>.

**Ejemplo:**

<body>
    <h1>Hola mundo</h1>
    <p>Este es un texto</p>
</body>

---

## h1 000006

**Tipo:** etiqueta  
**Función:** define el título principal de la página  

**Descripción:**

La etiqueta <h1> se utiliza para mostrar el título más importante dentro del contenido visible de la página.

Es el encabezado de mayor nivel y debe representar la idea principal del contenido.

Solo debería haber un <h1> principal por página para mantener una buena estructura.

**Ejemplo:**

<h1>Bienvenido a mi página</h1>

---

## h2 000007

**Tipo:** etiqueta  
**Función:** define un subtítulo o encabezado de segundo nivel  

**Descripción:**

La etiqueta `<h2>` se utiliza para mostrar títulos secundarios dentro de una página web.  
Representa la **jerarquía inmediata** debajo del `<h1>` y ayuda a organizar el contenido en secciones.

Se pueden usar múltiples `<h2>` en una página, cada uno para dividir diferentes secciones temáticas.

**Ejemplo:**

<h2>Sección de Productos</h2>

---

## p 000008

**Tipo:** etiqueta  
**Función:** define un párrafo de texto  

**Descripción:**

La etiqueta `<p>` se utiliza para mostrar bloques de texto dentro de la página web.  
Cada párrafo está separado del anterior y del siguiente, generando espacio vertical automáticamente.

Se usa para contenido general como descripciones, explicaciones o cualquier texto que quieras mostrar de forma organizada.

**Ejemplo:**

<p>Este es un párrafo de ejemplo donde explicamos algo importante sobre la página.</p>

---

## img 000009

**Tipo:** etiqueta  
**Función:** insertar una imagen en la página  

**Descripción:**

La etiqueta `<img>` permite mostrar imágenes dentro de la página web.

Es una etiqueta **autocontenida** (no tiene cierre) y requiere al menos el atributo `src` para indicar la ruta de la imagen.

Opcionalmente puede llevar atributos como:

- `alt` → texto alternativo si la imagen no carga  
- `width` → ancho de la imagen  
- `height` → alto de la imagen  

**Ejemplo:**

<img src="logo.png" alt="Logotipo de la empresa" width="200" height="100">

---

## a 000010

**Tipo:** etiqueta  
**Función:** crear enlaces a otras páginas o recursos  

**Descripción:**

La etiqueta `<a>` se utiliza para enlazar a otras páginas web, archivos o secciones dentro de la misma página.

Atributos importantes:

- `href` → define la URL o ruta del enlace  
- `target` → define dónde se abrirá el enlace (`_blank` para nueva pestaña)  
- `rel` → define la relación del enlace con el documento actual (ej: `noopener`, `nofollow`)  

**Ejemplo:**

<a href="https://www.ejemplo.com" target="_blank" rel="noopener">Visitar ejemplo</a>

---