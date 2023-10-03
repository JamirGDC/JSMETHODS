
# Video - Tutorial

[![Alt text](https://img.youtube.com/vi/Zr7rybX5d_E/0.jpg)](https://youtu.be/Zr7rybX5d_E)

# FOREACH

ForEach es un método en JavaScript que se utiliza para iterar sobre elementos de una lista (como un array) y ejecutar una función proporcionada una vez por cada elemento. Es una forma común de realizar operaciones en cada elemento de una lista sin tener que escribir un bucle for explícito.

```
// FOREACH

const num = [1, 23, 60, 46, 100];

num.forEach((numeros) =>{
    console.log(numeros);
});

```
# MAP

Map es otro método en JavaScript que se utiliza para iterar sobre elementos de una lista (como un array) y crear un nuevo array con los resultados de aplicar una función a cada elemento. A diferencia de forEach, map devuelve un nuevo array, en lugar de modificar el array original.

```
//MAP

const vegetales = ['tomate', 'cebolla', 'patata'];

const vegeupper = vegetales.map((upper) =>{
    return upper.toUpperCase();
});

console.log(vegeupper);
```
# FILTER


Filter es un método en JavaScript que se utiliza para filtrar elementos de un array basado en una condición especificada por una función de prueba. Este método devuelve un nuevo array que contiene solo los elementos del array original que cumplen con la condición establecida.

```
//FILTER

const cebolla = vegetales.filter((encontrarcebolla) => {
    return encontrarcebolla.includes('cebolla');
});

console.log(cebolla);
```
#REDUCE 

Es otro método en JavaScript que se utiliza para reducir un array a un solo valor. Permite aplicar una función a un acumulador y a cada elemento de un array (de izquierda a derecha) para reducirlos a un único valor. Este valor acumulado es retornado al final del proceso.

```
//reduce

const nummayor = num.reduce((inicio, numero) =>{
    return numero > inicio ? numero : inicio;

}, num[0]);

console.log(nummayor);
```



