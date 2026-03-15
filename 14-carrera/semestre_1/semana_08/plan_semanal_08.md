# Semana 08 — Funciones en JavaScript

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a utilizar funciones en JavaScript para
organizar el código en bloques reutilizables.

Las funciones permiten agrupar instrucciones
para ejecutarlas cuando sea necesario.

Durante esta semana se aprenderá:

- qué es una función
- cómo declarar funciones
- cómo ejecutar funciones
- parámetros
- retorno de valores

El objetivo es comenzar a escribir código estructurado
y reutilizable.

---

# Habilidades que se desarrollarán

Al finalizar la semana deberías poder:

- crear funciones
- reutilizar bloques de código
- usar parámetros
- retornar resultados
- organizar mejor programas

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Fundamentos de funciones.

Bloque 2 — 16:00 a 19:00  
Práctica con funciones en JavaScript.

---

# Día 1 — Qué es una función

## Bloque 1 — Concepto de función

Temas:

- qué es una función
- por qué se usan funciones
- reutilización de código

Ejemplo sin función:

console.log("Hola")
console.log("Hola")
console.log("Hola")

Ejemplo con función:

function saludar() {
console.log("Hola")
}

saludar()

Actividad:

Documento:

"Qué es una función en programación".

---

## Bloque 2 — Primera función

Crear función simple.

Ejemplo:

function mensaje() {
console.log("Estoy aprendiendo JavaScript")
}

mensaje()

Objetivo:

Comprender cómo ejecutar funciones.

---

# Día 2 — Parámetros

## Bloque 1 — Funciones con entrada

Temas:

- parámetros
- datos de entrada

Ejemplo:

function saludar(nombre) {
console.log("Hola " + nombre)
}

saludar("Benjamín")

Actividad:

Documento:

"Cómo funcionan los parámetros en funciones".

---

## Bloque 2 — Funciones personalizadas

Crear funciones que:

- saluden personas
- reciban edad
- generen mensajes personalizados

Objetivo:

Trabajar con datos de entrada.

---

# Día 3 — Retorno de valores

## Bloque 1 — return

Temas:

- retorno de información
- funciones que calculan resultados

Ejemplo:

function sumar(a, b) {
return a + b
}

let resultado = sumar(5, 3)

console.log(resultado)

Actividad:

Documento:

"Cómo funcionan los valores de retorno".

---

## Bloque 2 — Funciones matemáticas

Crear funciones que:

- sumen números
- resten números
- multipliquen números
- dividan números

Objetivo:

Construir calculadoras simples.

---

# Día 4 — Organización del código

## Bloque 1 — Modularidad

Temas:

- dividir programas en funciones
- organización del código
- reutilización

Ejemplo:

function calcularEdad(añoNacimiento) {
return 2026 - añoNacimiento
}

Actividad:

Documento:

"Cómo las funciones organizan los programas".

---

## Bloque 2 — Mini sistema

Crear funciones como:

- calcular edad
- verificar mayoría de edad
- generar mensaje final

Objetivo:

Construir programa usando varias funciones.

---

# Día 5 — Integración

## Bloque 1 — Reflexión técnica

Escribir documento:

"Cómo las funciones mejoran la programación".

Incluir:

- reutilización
- organización
- claridad del código

---

## Bloque 2 — Integración en el sitio

Agregar sección:

"Funciones en JavaScript".

Mostrar ejemplos como:

- funciones matemáticas
- funciones de saludo
- funciones de cálculo

Objetivo:

Documentar el aprendizaje.

---

# Entregables de la semana

Documentos:

- qué es una función
- funciones con parámetros
- retorno de valores
- organización con funciones
- reflexión semanal

Código:

- funciones funcionales

---

# Micro-proyecto de la semana

Proyecto:

Mini calculadora con funciones.

Características:

- función suma
- función resta
- función multiplicación
- función división

Tecnología:

JavaScript

---

# Conexión con el proyecto del semestre

Las funciones permiten:

- dividir programas grandes
- reutilizar lógica
- construir sistemas complejos

Son una de las herramientas más importantes
de cualquier lenguaje de programación.

---

# Evaluación personal

Al final de la semana responde:

1. ¿Puedo crear funciones?
2. ¿Puedo usar parámetros?
3. ¿Puedo retornar valores?
4. ¿Puedo organizar código con funciones?

Si la mayoría es **sí**, el progreso es correcto.

---

# Mentalidad de ingeniería

Practica durante esta semana:

- dividir problemas en funciones
- escribir código reutilizable
- organizar programas complejos
- pensar en módulos independientes