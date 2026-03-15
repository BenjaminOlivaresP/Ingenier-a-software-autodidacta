# Semana 13 — Eventos en JavaScript

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a manejar eventos en JavaScript para que
la página web pueda reaccionar a acciones del usuario.

Durante esta semana se aprenderá:

- qué es un evento
- eventos de clic
- eventos de teclado
- eventos de formularios
- ejecutar funciones cuando ocurre una acción

El objetivo es crear interacciones reales dentro del sitio web.

---

# Habilidades que se desarrollarán

Al finalizar la semana deberías poder:

- detectar acciones del usuario
- ejecutar código cuando ocurre un evento
- manejar clics en botones
- capturar información de formularios
- crear interacciones dentro de la página

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Conceptos de eventos.

Bloque 2 — 16:00 a 19:00  
Práctica con eventos en JavaScript.

---

# Día 1 — Qué es un evento

## Bloque 1 — Concepto

Temas:

- qué es un evento
- acciones del usuario
- respuesta del sistema

Ejemplos de eventos:

- clic
- escribir
- mover el mouse
- enviar formulario

Actividad:

Documento:

"Qué son los eventos en programación".

---

## Bloque 2 — Evento de clic

Ejemplo:

HTML

<button id="boton">Haz clic</button>

JavaScript

let boton = document.querySelector("#boton")

boton.addEventListener("click", function() {
console.log("Se hizo clic en el botón")
})

Objetivo:

Detectar cuando el usuario hace clic.

---

# Día 2 — Eventos con funciones

## Bloque 1 — Ejecutar funciones

Temas:

- funciones activadas por eventos

Ejemplo:

function saludar() {
console.log("Hola")
}

boton.addEventListener("click", saludar)

Actividad:

Documento:

"Funciones activadas por eventos".

---

## Bloque 2 — Botones interactivos

Crear botones que:

- cambien texto
- muestren mensajes
- ejecuten funciones

---

# Día 3 — Eventos de teclado

## Bloque 1 — Eventos de escritura

Temas:

- detectar cuando el usuario escribe
- eventos de teclado

Ejemplo:

input.addEventListener("input", function() {
console.log("El usuario está escribiendo")
})

Actividad:

Documento:

"Eventos de teclado en JavaScript".

---

## Bloque 2 — Práctica

Crear campo de texto que:

- muestre lo que el usuario escribe
- genere mensajes dinámicos

---

# Día 4 — Formularios

## Bloque 1 — Eventos de formulario

Temas:

- formularios HTML
- captura de datos

Ejemplo:

form.addEventListener("submit", function(event) {
event.preventDefault()
console.log("Formulario enviado")
})

Actividad:

Documento:

"Cómo funcionan los formularios en JavaScript".

---

## Bloque 2 — Formulario simple

Crear formulario que pida:

- nombre
- edad
- objetivo

Mostrar información en consola.

---

# Día 5 — Integración

## Bloque 1 — Reflexión técnica

Escribir documento:

"Cómo los eventos hacen interactivas las páginas web".

Incluir:

- ejemplos
- aplicaciones reales

---

## Bloque 2 — Integración en el sitio

Agregar sección:

"Eventos en JavaScript".

Mostrar ejemplos como:

- botón interactivo
- campo de texto dinámico
- formulario simple

Objetivo:

Documentar el aprendizaje.

---

# Entregables de la semana

Documentos:

- qué son los eventos
- eventos de clic
- eventos de teclado
- formularios
- reflexión semanal

Código:

- scripts con eventos

---

# Micro-proyecto de la semana

Proyecto:

Formulario interactivo.

Características:

- recibir nombre
- recibir edad
- mostrar mensaje personalizado

Tecnología:

JavaScript + DOM + eventos

---

# Conexión con el proyecto del semestre

Los eventos permiten:

- interacción con el usuario
- formularios dinámicos
- aplicaciones web funcionales

Son la base de todas las interfaces modernas.

---

# Evaluación personal

Al final de la semana responde:

1. ¿Puedo detectar eventos?
2. ¿Puedo manejar clics en botones?
3. ¿Puedo capturar información del usuario?
4. ¿Puedo ejecutar funciones con eventos?

Si la mayoría es **sí**, el progreso es correcto.

---

# Mentalidad de ingeniería

Practica durante esta semana:

- pensar en interacción usuario-sistema
- diseñar interfaces reactivas
- programar comportamientos dinámicos
- anticipar acciones del usuario