# Semana 3 — Middleware y Manejo de Solicitudes

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a utilizar middleware en Node.js para controlar el flujo de solicitudes, gestionar datos y preparar la estructura para aplicaciones backend más complejas.  
Esta semana se enfoca en la manipulación avanzada de requests y responses, así como la implementación de funciones intermedias que agilicen la gestión de rutas y datos.

Durante la semana se revisarán:

- concepto y utilidad de middleware
- middleware global y específico de rutas
- parsing de datos entrantes (JSON, URL-encoded)
- manejo de cabeceras HTTP
- validación básica de solicitudes

---

# Habilidades que se desarrollarán

Al finalizar la semana, el estudiante podrá:

- aplicar middleware en rutas y en la aplicación completa  
- recibir y procesar datos JSON y form-urlencoded  
- controlar flujo de solicitudes y respuestas  
- validar y transformar datos antes de llegar al endpoint  
- estructurar mejor el backend para proyectos futuros  

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Teoría y explicación de conceptos de middleware y flujo de solicitudes.

Bloque 2 — 16:00 a 19:00  
Práctica con Node.js y ejercicios de middleware y validación de datos.

---

# Día 1 — Introducción al middleware

## Bloque 1 — Conceptos

- qué es un middleware y para qué sirve
- middleware global vs local
- cómo se ejecuta dentro del ciclo de solicitud-respuesta

Actividad:

Documento:

“Introducción al middleware en Node.js”.

---

## Bloque 2 — Ejercicios

- crear middleware que registre cada solicitud en consola
- probar flujo de solicitudes a través de varias rutas
- experimentar con middleware global y específico

---

# Día 2 — Parsing de datos entrantes

## Bloque 1 — Conceptos

- body-parser y express.json()
- recepción de datos desde formularios y JSON
- diferencias entre application/json y application/x-www-form-urlencoded

Actividad:

Documento:

“Parsing de datos en Node.js con middleware”.

---

## Bloque 2 — Ejercicios

- recibir datos JSON en POST requests
- procesar datos de formularios HTML
- retornar respuestas personalizadas según contenido recibido

---

# Día 3 — Middleware para validación y control

## Bloque 1 — Conceptos

- validar datos antes de llegar al endpoint
- manejo de errores simples dentro de middleware
- orden de ejecución y flujo de rutas

Actividad:

Documento:

“Validación y control de solicitudes con middleware”.

---

## Bloque 2 — Ejercicios

- crear middleware que valide campos requeridos
- retornar errores claros si los datos no cumplen criterios
- probar flujo completo con Postman

---

# Día 4 — Middleware modular y reutilizable

## Bloque 1 — Conceptos

- crear funciones middleware reutilizables
- importar y usar middleware en distintos archivos
- buenas prácticas de organización

Actividad:

Documento:

“Middleware modular en Node.js”.

---

## Bloque 2 — Ejercicios

- separar middleware en archivos individuales
- usar middleware en varias rutas
- probar funcionalidad completa y flujo de datos

---

# Día 5 — Mini-proyecto de la semana

## Bloque 1 — Planificación

- diseñar microservicio con varias rutas
- incluir middleware de logging y validación
- definir datos esperados en solicitudes

## Bloque 2 — Desarrollo

- implementar middleware global y específico
- probar todas las rutas y validaciones
- documentar comportamiento y flujo de solicitudes

---

# Entregables de la semana

- Documento teórico sobre middleware y flujo de solicitudes  
- Mini-proyecto con middleware global y específico implementado  
- Ejercicios prácticos de validación y parsing de datos  

---

# Conexión con el semestre

Esta semana prepara al estudiante para:

- programación orientada a objetos en backend  
- conexión con bases de datos y CRUD avanzado  
- manejo de autenticación y seguridad  
- construcción de APIs más complejas y robustas

Una buena base en middleware asegura que la aplicación backend sea escalable y mantenible.

---

# Evaluación personal

Responder:

1. ¿Puedo crear middleware global y específico en Node.js?  
2. ¿Puedo recibir y procesar datos JSON y formularios correctamente?  
3. ¿Sé validar solicitudes y manejar errores con middleware?  
4. ¿Puedo organizar middleware modular y reutilizable para distintas rutas?  

Si la mayoría es **sí**, el estudiante está listo para continuar con la Semana 4 — Programación orientada a objetos en backend.