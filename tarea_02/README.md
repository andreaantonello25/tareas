# Tarea 2

**Nombre:** Andrea Antonello Monzón  
**Correo:** andrea.antonello@uc.cl

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QPtpKSxZx860I1EPtKkj4KkmB3c5kL6h?usp=sharing)

---

## Ejercicio 1

Este ejercicio lo realizamos en clases. Teníamos que organizar números desde el -100 hasta el 200.

Algo muy interesante es que tuvimos que poner hasta el número **201**, porque en `range`, Python **no incluye el número final**.

Entonces, si poníamos solamente: `for i in range(-100, 200):`, la secuencia llegaría desde el -100 hasta el 199.

---

## Ejercicio 2

El segundo ejercicio también lo realizamos en clases. Aquí lo que teníamos que hacer, basándonos en el ejercicio 1, era tomar esa misma secuencia que creamos pero ahora hacer que solo se impriman los números que son divisibles entre 6 con resto 0.

Aprendimos a usar el resto (`%`) y cómo `==` se usa para hacer una **comparación igualada**, a diferencia de `=`, que asigna un valor.

---

## Ejercicio 3

En este teníamos que realizar un código que sume dos números y diga si la suma es:

- “menor a 200”  
- “mayor a 200 y menor a 250”  
- o “mayor a 250”.

Un poco más abajo van a poder ver el “ejercicio 3.1”. Esto es porque el primero cumple exactamente con las instrucciones entregadas, pero decidí hacer el segundo para que esté un poco más ordenado y, más importante, para que también tome en cuenta la posibilidad de que **la suma sea igual a 200** o que **la suma sea igual a 250**.

Esta diferencia la hice porque me pareció pertinente, ya que en el primer código, cuando coloco 200 o 250, me dice que es “mayor” que ese número, cuando en verdad es igual al número.

En este código utilicé `int` y `input`, y las variantes `if`, `elif` y `else`, junto con `print`.

---

## Ejercicio 4

En este teníamos que crear un código que contenga una función, en donde se pregunte por la edad y el gusto por la música urbana. Dependiendo de la respuesta, debía decir si la persona tiene más o menos de 18 años, y si le gusta o no la música urbana.

Aquí también realicé un segundo código llamado “ejercicio 4.1”, por las mismas razones del anterior: para que si alguien tiene exactamente 18 años, se le diga que **tiene esa edad** y no que tiene menos.

Volví a utilizar `int` y `input`, así como `if`, `elif` y `else`, esta vez en el `return`. También se agregó el uso de `def`, la cual sirve para definir una función.

---

