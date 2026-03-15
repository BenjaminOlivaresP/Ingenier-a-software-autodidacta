# Semana 12 — Manipulación del DOM con JavaScript

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a manipular el DOM (Document Object Model)
para modificar páginas web utilizando JavaScript.

El DOM es la representación de la página HTML
que el navegador utiliza para interactuar con el contenido.

Durante esta semana se aprenderá:

- qué es el DOM
- cómo seleccionar elementos HTML
- cómo modificar contenido
- cómo cambiar estilos desde JavaScript
- cómo agregar nuevos elementos

El objetivo es que el sitio web deje de ser estático
y comience a ser dinámico.

---

# Habilidades que se desarrollarán

Al finalizar la semana deberías poder:

- seleccionar elementos del HTML
- modificar texto dentro de la página
- cambiar estilos usando JavaScript
- crear nuevos elementos dinámicamente
- controlar partes del sitio web con código

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Conceptos del DOM.

Bloque 2 — 16:00 a 19:00  
Práctica manipulando el sitio web.

---

# Día 1 — Qué es el DOM

## Bloque 1 — Concepto de DOM

Temas:

- qué es el DOM
- cómo el navegador interpreta HTML
- representación de la página como estructura

Ejemplo visual:

HTML → árbol de elementos

Actividad:

Documento:

"Qué es el DOM y cómo funciona".

---

## Bloque 2 — Seleccionar elementos

Aprender a seleccionar elementos del HTML.

Ejemplo:

document.querySelector("h1")

document.querySelector("p")

document.querySelector(".clase")

document.querySelector("#id")

Objetivo:

Acceder a elementos de la página.

---

# Día 2 — Modificar contenido

## Bloque 1 — Cambiar texto

Temas:

- modificar contenido HTML
- propiedades del DOM

Ejemplo:

let titulo = document.querySelector("h1")

titulo.textContent = "Nuevo título"

Actividad:

Documento:

"Cómo modificar contenido con JavaScript".

---

## Bloque 2 — Práctica

Cambiar textos dentro del sitio web.

Ejemplos:

- cambiar título
- cambiar párrafos
- mostrar mensajes nuevos

---

# Día 3 — Cambiar estilos

## Bloque 1 — Manipulación de estilos

Temas:

- modificar CSS desde JavaScript

Ejemplo:

let titulo = document.querySelector("h1")

titulo.style.color = "red"

titulo.style.fontSize = "40px"

Actividad:

Documento:

"Cómo cambiar estilos con JavaScript".

---

## Bloque 2 — Práctica

Modificar:

- colores
- tamaños
- fondos

Objetivo:

Ver cómo JavaScript puede cambiar la apariencia de la página.

---

# Día 4 — Crear elementos

## Bloque 1 — Elementos dinámicos

Temas:

- crear elementos HTML con JavaScript
- insertar contenido dinámico

Ejemplo:

let nuevoParrafo = document.createElement("p")

nuevoParrafo.textContent = "Este párrafo fue creado con JavaScript"

document.body.appendChild(nuevoParrafo)

Actividad:

Documento:

"Cómo crear elementos dinámicos".

---

## Bloque 2 — Práctica

Crear:

- nuevos párrafos
- nuevas secciones
- nuevos mensajes

Objetivo:

Generar contenido dinámicamente.

---

# Día 5 — Integración

## Bloque 1 — Reflexión técnica

Escribir documento:

"Cómo JavaScript puede controlar una página web".

Incluir:

- ejemplos
- aplicaciones reales

---

## Bloque 2 — Integración en el sitio

Agregar sección:

"Manipulación del DOM".

Mostrar ejemplos como:

- cambio de textos
- cambio de estilos
- creación de elementos

Objetivo:

Documentar el aprendizaje.

---

# Entregables de la semana

Documentos:

- qué es el DOM
- modificar contenido
- cambiar estilos
- crear elementos
- reflexión semanal

Código:

- scripts que manipulan el DOM

---

# Micro-proyecto de la semana

Proyecto:

Sistema que agregue mensajes dinámicos
a la página web.

Ejemplo:

botón → crea nuevo mensaje en la página.

Tecnología:

JavaScript + DOM

---

# Conexión con el proyecto del semestre

La manipulación del DOM permite:

- páginas dinámicas
- contenido interactivo
- aplicaciones web funcionales

Es una base fundamental del desarrollo web.

---

# Evaluación personal

Al final de la semana responde:

1. ¿Comprendo qué es el DOM?
2. ¿Puedo seleccionar elementos HTML?
3. ¿Puedo modificar contenido?
4. ¿Puedo crear elementos dinámicos?

Si la mayoría es **sí**, el progreso es correcto.

---

# Mentalidad de ingeniería

Practica durante esta semana:

- pensar en páginas dinámicas
- controlar el contenido desde código
- modificar estructuras de HTML
- crear interfaces interactivas