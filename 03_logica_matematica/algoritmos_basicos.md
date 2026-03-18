# Pensamiento computacional

El pensamiento computacional es la capacidad de resolver problemas
de manera lógica, estructurada y paso a paso, como lo haría un computador.

Se basa en cuatro pilares fundamentales:

- descomposición
- abstracción
- reconocimiento de patrones
- diseño de algoritmos

---

## Descomposición

Consiste en dividir un problema grande en partes más pequeñas.

Ejemplo:

Calcular promedio:

- obtener números
- sumarlos
- dividir el resultado

---

## Abstracción

Consiste en enfocarse en lo importante e ignorar lo innecesario.

Ejemplo:

Para saber si un número es par:

- no importa el número exacto
- solo importa si es divisible por 2

---

## Reconocimiento de patrones

Consiste en identificar similitudes entre problemas.

Ejemplo:

- promedio de 3 números
- promedio de 10 números

👉 ambos siguen la misma lógica

---

## Diseño de algoritmos

Consiste en crear pasos ordenados para resolver un problema.

Todos los ejercicios a continuación son ejemplos de esto.


------


# Algoritmos básicos

Este documento contiene ejercicios de pensamiento computacional utizando pseudocódigo.

El objetivo es aprender a descomponer problemas en pasos lógicos que un computador pueda ejecutar.



## Ejercicio 1 - Determinar si un número es par o impar

Problema:
Determinar si un número ingresado por el usuario es par o impar.

Pseudocódigo:

INICIO

leer numero

si numero % 2 == 0 entonces
    mostrar "El número es par"
si no
    mostrar "El número es impar"

FIN

---

## Ejercicio 2 - Área de un rectángulo

Problema:
Calcular el área de un rectángulo a partir de su base y altura.

Pseudocódigo:

INICIO
leer base
leer altura

area = base * altura

mostrar area

FIN

---

## Ejercicio 3 — Número mayor

Problema:
Determinar cuál número es mayor entre dos números.

Pseudocódigo:

INICIO

leer numero1  
leer numero2  

si numero1 > numero2 entonces  
    mostrar "numero1 es mayor"  

si numero2 > numero1 entonces  
    mostrar "numero2 es mayor"  

si numero1 == numero2 entonces  
    mostrar "los números son iguales"  

FIN

-------

## Ejercicio 4 — Promedio de números

Problema:
Calcular el promedio de una lista de números.

Pseudocódigo:

INICIO

definir suma = 0
definir contador = 0

para cada número en la lista
    suma = suma + número
    contador = contador + 1

promedio = suma / contador

mostrar promedio

FIN

----

## Ejercicio 5 - Clasificación de número

**Problema:**  
Determinar si un número es positivo, negativo o cero.

**Pseudocode:**

INICIO

read number

if number > 0 then  
    print "positive"

else if number < 0 then  
    print "negative"

else  
    print "zero"

FIN
 
----

## Ejercicio 6 - Validación de edad para votar

**Problema:**  
Determinar si una persona puede votar según su edad.

**Pseudocode:**

INICIO

read age

if age >= 18 then  
    print "can vote"

else  
    print "cannot vote"

FIN