# Vocabulario HTML

---

## html

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

## head

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

## title

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

## link

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

## body

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