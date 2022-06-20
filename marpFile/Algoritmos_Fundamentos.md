---
title       : Algoritmos
author      : kevin Pilo
description : Algoritmos
marp        : true
paginate    : true
theme       : default 
---
<style>
    :root {
    font-family: 'Roboto Condensed', sans-serif;
    font-weight: initial;
    background-color: #002e4f;
    color: #ffff;
    text-align: center;
}

h1{
    color: #ffffff;
    
}
</style>


# Algoritmos
![bg width:500px height:400px left:50%](https://images.pexels.com/photos/9028920/pexels-photo-9028920.jpeg?cs=srgb&dl=pexels-kindel-media-9028920.jpg&fm=jpg)

---


# 1 
# 2 
# 3 
# 4 . .



---


# Preciso



# Definido



# Finito





---


# Gráfico  y  No Gráfico





---

# Metodología para

# crear un algoritmo

---


# 1.  Definir el problema




# 2.  Analizar el problema




# 3. Diseñar el algoritmo




# 4. Prueba de escritorio



---

## Calcular la hipotenusa de un

## triángulo rectángulo

---

# Este es elproblema

### Calcular la hipotenusa de un

### triángulo rectángulo

---
![bg width:100% height:100%](../assets/al1.png)

---



![bg width:100% height:100%](../assets/al2.png)


---
# Pasos para resolverlo
● Necesito el valor de los catetos.

● Elevar al cuadrado el valorde los catetos.

● Sumo los dosvalores.

● Saco raíz cuadrada del resultado.

● Imprimo el valor de la hipotenusa.


---

# Prueba deescritorio

 h^2 = 3^2 + 42
 h^2 = 9 + 16
 h^2 = 25
 h =√25
 h = 5

---



# Diagramas de flujo



---
![bg width:100% height:100%](../assets/al3.png)








---





# Variables  y  Constantes
![bg width:100% height:100% left:50%](../assets/al4.png)





---




![bg width:100% height:100% ](../assets/al5.png)





---


![bg width:100% height:100% ](../assets/al6.png)




---




# Tipos de datos




---


![bg width:100% height:100% ](../assets/al7.png)







---
# Strings y concatenación

---

# “Yo soy una cadena

# de texto”




---

# Char y String


## **‘H’** - Carácter

## **“Hola”** - Cadena




---


# Números

## Y operacionesmatemáticas básicas

---


int, float, short, long





---
# Suma

## valor + valor

## 5 + 7





---
# Resta

## valor - valor

## 9 - 6



---
# Multiplicación


## valor *valor
## 3 * 4


---
# División


## valor /valor
## 10 / 2

---


# El tipo de dato puede afectar el resultado

---
# Operaciones

# matemáticas

# compuestas

---

# 5 - 3 * 2 + 4 - 4 / 2


# 5 - 3 * 2 + 4 - 4 / 2

# 5 - 6 + 4 - 2 = 1


# (5 - 3 * 2) + (4 - 4 / 2) + 8


# (5 - 3 * 2) + (4 - 4 / 2) + 8

# (5 - 6) + (4 - 2) + 8 - 1 + 2 + 8 = 9




---

# True y false
Booleanos y tablas de verdad


---
# Tablas de verdad

¿Qué son?


---
![bg width:100% height:100% ](../assets/al8.png)









---



![bg width:100% height:100% ](../assets/al9.png)







---

![bg width:100% height:100% ](../assets/al10.png)







---

![bg width:100% height:100% ](../assets/al11.png)







---



![bg width:100% height:100% ](../assets/al12.png)




---



![bg width:100% height:100% ](../assets/al13.png)




---




![bg width:100% height:100% ](../assets/al14.png)







---

---



```
Valor de
proposición 1
```
```
Valor de
proposición 2 ConectivaLógica
```
```
V F Resultado
```
```
F V Resultado
```
Composición


P ~P

V F

F V

Negación

Unaproposición que es
verdadera esfalsa.


Conjunción

Es verdadera solo si
ambas sonverdaderas,
y es falsa cuando al
menos uno de los
valores esfalso.

```
p q p^q
v and v v
v and f f
```
f and v f

f and f f


Disyunción inclusiva

Es verdaderacuando
por lo menos una es
verdadera; de lo
contrario, seráfalsa.

```
p q p ν q
v or v v
v or f v
```
f or v v

f or f f


Disyunción exclusiva

Es falsa si ambos
componentes son
verdaderos ofalsos.

```
p q p ν q
v xor v f
v xor f v
```
f xor v v

f xor f f


Condicional

Devuelve falso cuando
el primer valor es
verdadero y el segundo
falso.

```
p q p->q
v then v v
v then f f
```
f then v v

f then f v


Bicondicional

Es verdadera cuando
ambas proposiciones
son verdaderaso ambas
falsas.

```
p q p<->q
v if v v
v if f f
```
f if v f

f if f v


Vectores yarreglos

# Arrays


Conjunto de elementos

del mismo tipo

ordenados en **fila**


0 1 2 3 4 5 6 7 8


0 1 2 3 4 5 6 7 8


0 1 2 3 4 5 6 7 8

9


A M B N C O D P E


A M B N C O D P E

0


a b c d e f

79 8 56

A M B N C O D P E X

```
Pueden tener diferentestamaños
```

a b c d e f

8 56 79

A B C D E M N O P X

```
Se puedenordenar
```

A M B N C O D P E X

```
Se puedenrecorrer
```

a b c d e f

3

Se puedeacceder a unaposición **específica**


# Estructuras

# de control


# Nos ayudan a

# construir el flujo de

# nuestras tareas


If /Else


If /Else

Switch


If / Else

Switch

While


If / Else

Switch

While

Do While


If / Else

Switch

While

Do While

For


If /Else


Si x < 20 entonces

retorna **“ok”**


Si x < 20 entonces

```
retorna “ok”
Sino
```

## Si x < 20 entonces

## retorna “ok”

```
Si no
```
# retorna “no”


# Puedes usar

# operadores de

# comparación


# Switch


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


switch(numero) {
case 1:
“El número es 1”
break;
case 2:
“El número es 2”
break;
case 3:
“El número es 3”
break;
default:
“El número es mayor a 3”
}


# Excepciones


Es un eventoanormal

que ocurre durantela

ejecución

No esun “else”.No funciona como un “else”


La puedes invocar en el puntoque desees

# throw


Intenta hacer X pero si falla haz Y

# Try ... catch


Lo quesucede después del try y catch

# finally


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


try {
Decir hola
} catch(e) {
Ups, no pude decir hola :(
} finally {
¡Todo va a estar bien!
}


```
for, while, dowhile
```
# ¿Qué es un ciclo?


Es una estructura de control que ejecuta
un bloque de instrucciones de manera
repetida.

Ciclo


for(x=0; x<=30; x++)

# For


for (x=0; x<=30;x++)


for (x=0; x<=30;x++)


for (x=0; x<=30;x++)


for (x=0; x<=30;x++)

```
Estoy en laposición x
```

while (x <=10)

# While


while (x<= 10)


while (x<= 10)

```
Soymenor que 10 x++
```

```
do {
i = i + 1;
saludo
}while (i < 5);
```
# Do ... while


do {

i ++

Aquí hago algo

} while (i < 5)


do {

i ++

Aquí hago algo

} while (i < 5)


# Funciones


Bloques de código

que realizan una

actividad **específica**


# ¿Para qué sirven

# las funciones?


● Modularizar

● Optimizar

● Organizar

● Encapsular

Sirven para:


function decirHola()

return **“hola”**

```
Función simpley específica
```

function muestraNombre(nombre)

return nombre

```
Función conparámetro
```

```
Sí,parámetro
```
# ¿Parámetro?


valor1 y valor2 sonlos parámetros
de lafunción.

```
function suma(valor1, valor2)
return valor1 + valor 2
```

# Los parámetros son

# diferentes a los

# argumentos


```
Sí,argumentos
```
# ¿Argumentos?


3 y 1 sonlos argumentos, o sea,el valor
que sele asignóa los parámetros alusar
esa función.

suma(3, 1)


```
Puedenser tansimples otan
complejas comoqueramos
```
# Volviendo a las

# funciones


```
Y ocuparse de una sola tarea
```
# Pero siempre deben

# ser puntuales


```
Másque una buena práctica
```
# Modularización

# del código


Necesitas tener tu

código modularizado


Deja que cada

bloque haga unatarea

particular


Esto permitirá

que sea escalable


Seguramente

estará optimizado


Reutiliza y dinamiza


A nivel defunciones

y archivos


```
Funcionesque sellaman a símismas
```
# ¿Qué es recursividad?


```
Porque pueden serinfinitas
```
# Hay que tener

# precaución


# Lo mejor es

# condicionarlas y

# usarlas sabiamente


cuentaRegresiva(numero):
numero -= 1
if numero > 0:
muestra numero
cuentaRegresiva(numero)
else:
muestra "Feliz año nuevo"


# Diferencias entre

# lenguajes de

# programación


```
Abre tu mentea la lógica de lo
que debeshacer
```
# No te quedes

# con un lenguaje

# exclusivamente


# Diferencias

# sintácticas


# Finalización

# de líneas


# Tipado


# Indentación


# Corchetes


# La lógica es lo

# más importante
