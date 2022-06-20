# Lógica general 
1. Describa brevemente como resolvería el siguiente problema en un programa de 
computadora. (Únicamente la descripción de qué es lo que haría usted, no lo 
programe). Sea lo más especifico posible.

En una tienda de productos de limpieza se venden detergentes líquidos por ML, y se 
tienen botellas de 100ML, 250ML, 350ML, 500ML. Hay cierta existencia de cada una de 
las botellas. 

| CAPACIDAD   | CANTIDAD  |
| ----------- | --------- |
|   100ML     |          7|
|   250ML     |         15|
|   350ML     |          5|
|   500ML     |          3|

1. ¿Qué haría usted para que cuando un cliente compre algún producto se utilicen 
la menor cantidad de botellas, y se desperdicie la menor cantidad de espacio en 
las mismas.?


2. Plasme la descripción de su algoritmo.


3. Ejemplifique cómo distribuiría el liquido en los contenedores de la tabla de arriba 
con las siguientes compras ficticias, siguiendo su propuesta.


![img](../assets/ac1.png)


2. 👩‍💻 estás trabajando en un sistema operativo para ser usado en el taller de Santa Claus 🎅.

    Se ha dado cuenta que en el taller nadie le presta atención a los nombres de los ficheros y a veces intentan guardar el mismo fichero más de una vez... así que es importante que gestionemos bien los nombres duplicados.

    Tenemos que crear una función que al pasarnos un array de nombres de archivo devolvamos un array con el mismo número de elementos pero donde los nombres que se repetían se anexe al final (k) donde k sería el número de veces que se encontró repetido.

    Lo mejor es que veamos un ejemplo:

```python
files = ['photo', 'postcard', 'photo', 'photo', 'video']
fixFiles(files) # ['photo', 'postcard', 'photo(1)', 'photo(2)', 'video']

files2 = ['file', 'file', 'file', 'game', 'game']
fixFiles(files2) = ['file', 'file(1)', 'file(2)', 'game', 'game(1)']

# ojo que los elfos ya tenían archivos con (1)... ¡y pueden estar repetidos!
files3 = ['file', 'file(1)', 'icon', 'icon(1)', 'icon(1)']
fixFiles(files3) # ['file', 'file(1)', 'icon', 'icon(1)', 'icon(1)(1)']
```
   Se le pide realizar  el algoritmo para la implementacion la funcion descrita anteriormente.


