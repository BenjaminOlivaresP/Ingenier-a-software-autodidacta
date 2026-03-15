# Semana 8 — Autenticación y seguridad básica

Duración: 5 días  
Horas diarias: 6  
Total semanal: 30 horas

---

# Objetivo de la semana

Aprender a proteger aplicaciones backend mediante autenticación de usuarios y buenas prácticas de seguridad.  
El estudiante desarrollará la capacidad de manejar accesos, proteger rutas y validar datos de manera segura.

Durante la semana se revisarán:

- conceptos de autenticación y autorización  
- hashing de contraseñas  
- manejo de sesiones y tokens  
- protección de rutas en Node.js  
- buenas prácticas de seguridad básicas  

---

# Habilidades que se desarrollarán

Al finalizar la semana, el estudiante podrá:

- implementar registro y login de usuarios  
- almacenar contraseñas de forma segura usando hashing  
- generar y validar tokens de acceso (JWT)  
- proteger rutas y endpoints sensibles  
- aplicar validaciones de entrada para evitar vulnerabilidades comunes  

---

# Estructura diaria

Bloque 1 — 11:00 a 13:00  
Teoría sobre autenticación, hashing y seguridad de rutas.

Bloque 2 — 16:00 a 19:00  
Práctica implementando login, registro y protección de endpoints.

---

# Día 1 — Conceptos de autenticación y autorización

## Bloque 1 — Teoría

- diferencia entre autenticación y autorización  
- flujo de login y registro  
- conceptos de tokens y sesiones  

Actividad:  
Documento: “Fundamentos de autenticación y seguridad en backend”.

## Bloque 2 — Ejercicios

- analizar ejemplos de flujo de login y registro  
- diagramar flujo de autenticación de una aplicación simple  

---

# Día 2 — Hashing de contraseñas

## Bloque 1 — Teoría

- importancia de no guardar contraseñas en texto plano  
- uso de bcrypt o librerías equivalentes  
- salt y rounds en hashing  

Actividad:  
Documento: “Hashing seguro de contraseñas”.

## Bloque 2 — Ejercicios

- implementar registro de usuarios con hashing  
- verificar contraseñas al iniciar sesión  

---

# Día 3 — Generación y validación de tokens

## Bloque 1 — Teoría

- JSON Web Tokens (JWT)  
- creación y verificación de tokens  
- expiración y revocación de tokens  

Actividad:  
Documento: “Uso de JWT para autenticación”.

## Bloque 2 — Ejercicios

- generar token al iniciar sesión  
- proteger rutas usando middleware de validación de token  

---

# Día 4 — Protección de rutas y validación de datos

## Bloque 1 — Conceptos

- middleware en Node.js para proteger endpoints  
- validación de entrada de datos  
- prevención de ataques comunes: SQL Injection, XSS  

## Bloque 2 — Ejercicios

- implementar middleware para rutas protegidas  
- validar campos de entrada en login y registro  
- probar seguridad básica de la API  

---

# Día 5 — Consolidación y mini-proyecto

## Bloque 1 — Integración

- integrar registro, login y rutas protegidas en mini-proyecto  
- aplicar hashing y JWT  
- probar flujo completo de autenticación  

## Bloque 2 — Buenas prácticas y revisión

- refactorizar código para modularidad  
- asegurar manejo correcto de errores  
- preparar documentación de endpoints protegidos  

---

# Entregables de la semana

- Documento de conceptos de autenticación y seguridad  
- Código de ejemplo con registro, login y protección de rutas  
- Mini-proyecto funcional con usuarios autenticados  

---

# Conexión con el semestre

Esta semana prepara al estudiante para:

- diseñar APIs RESTful seguras (Semana 9 y 10)  
- implementar CRUD completo con usuarios y datos protegidos  
- aplicar buenas prácticas de seguridad en todos los proyectos backend  

---

# Evaluación personal

Responder:

1. ¿Puedo implementar registro y login de usuarios con seguridad?  
2. ¿Sé generar y validar tokens de acceso correctamente?  
3. ¿Protejo rutas y endpoints sensibles de manera efectiva?  
4. ¿Aplico buenas prácticas de validación y manejo de errores?  

Si la mayoría es **sí**, el estudiante está listo para continuar con la **Semana 9 — APIs RESTful: diseño y consumo**.