# Semana 11 — Manejo de errores y logging

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a manejar errores de manera efectiva y registrar eventos importantes en aplicaciones backend con Node.js.  
El estudiante desarrollará buenas prácticas para depuración, estabilidad y mantenimiento del sistema.

Durante la semana se estudiará:

- tipos de errores en Node.js  
- manejo de errores con `try/catch`  
- errores asincrónicos y promesas rechazadas  
- creación de middlewares de manejo de errores  
- logging de eventos y errores  
- buenas prácticas de depuración y monitoreo  

---

# Habilidades que se desarrollarán

Al finalizar la semana, el estudiante podrá:

- detectar y manejar errores en rutas y funciones  
- implementar middlewares de manejo de errores en Express  
- registrar eventos y errores en archivos o consola  
- diferenciar errores de servidor y de cliente  
- aplicar buenas prácticas de mantenimiento y monitoreo  

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Teoría y ejemplos guiados de manejo de errores.

Bloque 2 — 16:00 a 19:00  
Práctica con ejercicios de logging y depuración.

---

# Día 1 — Tipos de errores

## Bloque 1 — Teoría

Temas:

- errores de sintaxis vs errores de ejecución  
- errores de lógica  
- errores de cliente vs errores de servidor  
- errores en código asincrónico  

Actividad:

Documento:  
"Clasificación y tipos de errores en Node.js"

---

## Bloque 2 — Ejercicios

Práctica:

- generar errores controlados  
- diferenciar errores capturables de no capturables  
- observar comportamiento en la consola  

---

# Día 2 — Manejo de errores con try/catch

## Bloque 1 — Conceptos

Temas:

- bloques `try/catch`  
- manejo de errores en funciones y rutas  
- uso de `throw` para generar errores  

Actividad:

Documento:  
"Manejo básico de errores con try/catch en Node.js"

---

## Bloque 2 — Ejercicios

Práctica:

- envolver código crítico en `try/catch`  
- probar manejo de errores en rutas Express  
- capturar errores de operaciones de base de datos  

---

# Día 3 — Middleware de errores en Express

## Bloque 1 — Conceptos

Temas:

- definición de middleware de errores  
- orden de ejecución de middlewares  
- envío de mensajes claros al cliente  
- manejo de errores global y local  

Actividad:

Documento:  
"Middlewares de manejo de errores en Express"

---

## Bloque 2 — Ejercicios

Práctica:

- crear middleware global para capturar errores  
- probar rutas que lancen errores  
- enviar respuestas con códigos HTTP adecuados  

---

# Día 4 — Logging de eventos y errores

## Bloque 1 — Conceptos

Temas:

- registrar errores y eventos importantes  
- diferencias entre consola y archivos  
- librerías de logging (`winston`, `morgan`)  
- buenas prácticas de registro y monitoreo  

Actividad:

Documento:  
"Logging de errores y eventos en aplicaciones Node.js"

---

## Bloque 2 — Ejercicios

Práctica:

- implementar logs de rutas y errores  
- registrar operaciones CRUD importantes  
- crear archivo de logs y verificar información registrada  

---

# Día 5 — Integración y revisión

## Bloque 1 — Consolidación

- unir manejo de errores y logging en una aplicación completa  
- asegurar que todas las rutas manejan errores correctamente  
- validar mensajes y códigos HTTP  

## Bloque 2 — Buenas prácticas y documentación

- comentar código y explicar lógica de manejo de errores  
- documentar uso de logging y middleware  
- preparar mini-guía de mantenimiento para desarrolladores  

---

# Entregables de la semana

- Código con manejo de errores implementado  
- Middleware de errores en Express  
- Logs de eventos y errores  
- Documentación sobre errores y logging  

---

# Conexión con el semestre

Esta semana sienta las bases para:

- testing de aplicaciones (Semana 12)  
- despliegue confiable de servicios backend  
- seguridad y estabilidad en proyectos completos  

---

# Evaluación personal

Responder:

1. ¿Puedo identificar y clasificar errores correctamente?  
2. ¿Puedo manejar errores con `try/catch` y middlewares?  
3. ¿Sé registrar eventos y errores de manera eficiente?  
4. ¿Mi código es más estable y mantenible?  

Si la mayoría es **sí**, el estudiante está listo para continuar con la **Semana 12 — Testing básico de aplicaciones**.