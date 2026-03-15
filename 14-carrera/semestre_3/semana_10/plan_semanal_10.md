# Semana 10 — CRUD completo con Node.js y SQL

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Implementar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) completas en un backend con Node.js y bases de datos SQL.  
El estudiante aprenderá a conectar rutas con la base de datos, manejar consultas y asegurar que los datos se gestionen de manera correcta y eficiente.

Durante la semana se trabajará en:

- conexión de Node.js con SQL  
- creación de tablas y relaciones básicas  
- operaciones CREATE, READ, UPDATE y DELETE  
- consultas parametrizadas y prevención de inyecciones SQL  
- integración de endpoints con la base de datos  

---

# Habilidades que se desarrollarán

Al finalizar la semana, el estudiante podrá:

- crear y gestionar tablas en SQL  
- conectar Node.js con bases de datos SQL  
- implementar endpoints CRUD completos  
- validar datos de entrada antes de guardarlos  
- asegurar consistencia y seguridad en las operaciones de la base de datos  

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Teoría y práctica inicial en SQL y conexión con Node.js.

Bloque 2 — 16:00 a 19:00  
Desarrollo de endpoints CRUD y pruebas integrales.

---

# Día 1 — Conexión de Node.js con SQL

## Bloque 1 — Teoría

- introducción a bases de datos relacionales  
- conexión de Node.js con SQL usando `mysql2` o `pg`  
- configuración de pool de conexiones y manejo de errores  

## Bloque 2 — Ejercicios

- crear base de datos de ejemplo: usuarios y tareas  
- establecer conexión y probar consultas simples  

---

# Día 2 — Operación CREATE

## Bloque 1 — Teoría

- INSERT en SQL  
- parámetros y consultas preparadas  
- validación de datos antes de insertar  

## Bloque 2 — Ejercicios

- implementar endpoint POST para crear usuarios y tareas  
- probar inserciones desde Postman y frontend  

---

# Día 3 — Operación READ

## Bloque 1 — Teoría

- SELECT básico y filtrado  
- ordenamiento y búsqueda de registros  
- manejo de errores y resultados vacíos  

## Bloque 2 — Ejercicios

- implementar endpoint GET para listar usuarios y tareas  
- agregar filtros por ID o estado  
- mostrar resultados en JSON  

---

# Día 4 — Operaciones UPDATE y DELETE

## Bloque 1 — UPDATE

- actualizar registros existentes  
- validación de datos y manejo de errores  

## Bloque 2 — DELETE

- eliminar registros de manera segura  
- prevenir eliminación accidental o masiva  
- pruebas integrales de actualización y borrado  

---

# Día 5 — Integración y prueba completa

## Bloque 1 — Consolidación CRUD

- unificar endpoints CRUD en una aplicación completa  
- modularizar controladores y rutas  
- pruebas integrales con frontend y Postman  

## Bloque 2 — Buenas prácticas y documentación

- comentar código y explicar lógica  
- documentar endpoints CRUD  
- preparar mini-guía de uso para usuarios y desarrolladores  

---

# Entregables de la semana

- Código completo con endpoints CRUD implementados  
- Base de datos SQL de ejemplo  
- Documentación de los endpoints y su funcionamiento  

---

# Conexión con el semestre

Esta semana sienta la base para:

- manejar errores de manera avanzada (Semana 11)  
- implementar autenticación y seguridad en operaciones CRUD  
- construir aplicaciones backend totalmente funcionales  

---

# Evaluación personal

Responder:

1. ¿Puedo crear registros en la base de datos correctamente?  
2. ¿Puedo leer y filtrar datos de manera eficiente?  
3. ¿Sé actualizar y eliminar registros de forma segura?  
4. ¿Mi código está modular y documentado para futuras integraciones?  

Si la mayoría es **sí**, el estudiante está listo para continuar con la **Semana 11 — Manejo de errores y logging**.