# Metodos-de-array-ejercicios

## For Each

### 1
* Tenemos un array en una variable `playlist` con una lista de canciones de un disco.
* Recorrer la lista con la función **forEach** y mostrarlas una por una utilizando `console.log()`

```js
const playlist = ["Concrete and Gold", "The Line", "Sunday Rain", "Happy Ever After (Zero Hour)", "Arrows", "Dirty Water", "La Dee Da", "The Sky Is a Neighborhood", "Make It Right", "Run", "T-Shirt"];
```

### 2

* Tenemos un array en una variable `librosDeJS` con una lista de libros de javascript.
* Queremos saber la cantidad de libros que tenemos en el array
* Nos pidieron que evitemos usar la propiedad `length` para contar los elementos de un array y que tenemos que usar si o si un `forEach`
* Completá el siguiente código para que funcione el último `console.log()` y muestre el mensaje **Mi lista de libros de JavaScript tiene 9 libros**

```js
const librosDeJS = [
  'JavaScript for Kids: A Playful Introduction to Programming',
  'Composing Software',
  'Eloquent JavaScript: A Modern Introduction to Programming',
  'JavaScript: The Good Parts',
  'Programming JavaScript Applications: Robust Web Architecture with Node, HTML5, and Moderns JS Libraries',
  'Effective JavaScript: 68 Specific Ways to Harness the Power of JavaScript',
  'JavaScript: The Definitive Guide',
  'You Don’t Know JS',
  'JavaScript Allongé: The Six Edition'
];

/// ¡escribir en este espacio la solución del ejercicio!

console.log('Mi lista de libros de JavaScript tiene ' + totalLibros + ' libros');
```

### 3
* Tenemos un array en una variable `playlist` con una lista de canciones de un disco.
* Recorrer la lista con la función **forEach** y mostrar la posición y el nombre de la canción utilizando un `console.log()`

```js
const playlist = ["Concrete and Gold", "The Line", "Sunday Rain", "Happy Ever After (Zero Hour)", "Arrows", "Dirty Water", "La Dee Da", "The Sky Is a Neighborhood", "Make It Right", "Run", "T-Shirt"];

/// completá acá el código

// resultado esperado
// 0 - Concrete and Gold
// 1 - The Line
// 2 - Sunday Rain
// 3 - Happy Ever After (Zero Hour)
// 4 - Arrows
// 5 - Dirty Water
// 6 - La Dee Da
// 7 - The Sky Is a Neighborhood
// 8 - Make It Right
// 9 - Run
// 10 - T-Shirt
```

### 4
* Tenemos un array llamado `numbers` con números enteros al azar.
* Queremos calcular la suma de todos los números que están en el array.
* Por ejemplo: Si tenemos `[1, 2, 3]`, la suma de todos los números es **6**
* Es necesario utilizar `forEach` para conseguir la suma

```js
const numbers = [6, 1, 34, 94, 3, 17];
let sum = 0;

// codea debajo de este comentario la solucion al ejercicio

console.log(sum);
// deberia mostrar 155
```

### 5
* Tenemos un array llamado `notasDeTPs` con números del 1 al 10, que representan las notas de los distintos trabajos prácticos entregados por Grace Hopper en el curso de Ada.
* Queremos calcular la nota promedio final de trabajos prácticos _(el promedio se calcula sumando todas las notas y dividiéndolo por la cantidad de notas)_.
* Por ejemplo: Si tenemos `[7, 8, 9, 10]`, la nota final es **8.5**
* Es obligatorio utilizar `forEach` para conseguir el promedio

```js
const notasDeTPs = [4, 7, 8, 5, 10];
let notaFinal = 0;

// codea debajo de este comentario la solucion al ejercicio

console.log(notaFinal);
// deberia mostrar 6.8
```

### 6

* Tenemos un array en una variable `masNumeros` con números al azar.
* También tenemos dos arrays vacios en las dos variables `numerosPares` y `numerosImpares`.
* Recorré el array `masNumeros` (**utilizando forEach**) y:
  * Si el número es par, agregalo al array `numerosPares`
  * Si el número es impar, agregalo al array `numerosImpares`
* Por ejemplo: Si tenemos `[7, 8, 9, 10]`, `numerosPares` quedaría `[8, 10]` y `numerosImpares` quedaría `[7, 9]`

```js
const masNumeros = [ 43, 11, 18, 46, 44, 37, 42, 29, 9, 3, 37, 0, 40, 10, 38, 34, 25, 40, 4, 32 ];
const numerosPares = [];
const numerosImpares = [];

// SOLUCION

console.log("pares: ", numerosPares);
console.log("impares: ", numerosImpares);
// deberias tener como resultado
// pares: [18, 46, 44, 42, 0, 40, 10, 38, 34, 40, 4, 32]
// impares: [43, 11, 37, 29, 9, 3, 37, 25]
```

### 7

* Tenemos un array en una variable `valores` con números al azar.
* También tenemos un array vacio en la variable `dobles`.
* Recorré el array `valores` (**utilizando forEach**) y guardá, en el mismo orden, cada número pero multiplicándolo por 2.
* Por ejemplo: Si tenemos `[1, 4, 7]`, `dobles` quedaría `[2, 8, 14]`

```js
const valores = [ 6, 0, 5, 2, 3, 8, 7, 4, 1, 9 ];
const dobles = [];

// codea aca tu solución al ejercicio

console.log("valores: ", valores);
console.log("dobles: ", dobles);
// deberias tener como resultado
// valores:  [ 6, 0, 5, 2, 3, 8, 7, 4, 1, 9 ]
// dobles:  [ 12, 0, 10, 4, 6, 16, 14, 8, 2, 18 ]
```

## Map

### 1

* Tenemos un array en una variable `numeros` con números al azar.
* Usá la función `map` para crear un nuevo array incrementando cada valor del array en 10, y guardarlo en la variable `numerosMasDiez`
* Mostrar por consola el array original y el nuevo

```js
const numeros = [1, 2, 3, 4, 5];

let numerosMasDiez;

// codear acá la solución del ejercicio


console.log(numeros); // [1, 2, 3, 4, 5]
console.log(numerosMasDiez); // [11, 12, 13, 14, 15]
```

### 2
* Tenemos un array en una variable `numeros` con números al azar.
* Usar la función `map` para crear un nuevo array multiplicando cada valor del array por 2, y guardarlo en la variable `dobles`
* Mostrar por consola el array original y el nuevo

```js
const numeros = [3, 7, 13, 99];

// codear acá la solución del ejercicio


console.log(numeros); // [3, 7, 13, 99]
console.log(dobles); // [6, 14, 26, 198]
```

### 3

* Tenemos un array en una variable `frases` con frases al azar.
* Usar la función `map` para crear un nuevo array donde cada frase empiece y termine con signo de exclamación.
* Mostrar por consola el array original y el nuevo

```js
const frases = ['Labore sea dolor.', 'Justo rebum dolor.', 'Stet lorem amet.'];

// codear acá la solución del ejercicio


console.log(frases); // ['Labore sea dolor.', 'Justo rebum dolor.', 'Stet lorem amet.']
console.log(frasesExclamadas); // [ '¡Labore sea dolor.!', '¡Justo rebum dolor.!', '¡Stet lorem amet.!' ]
```

### 4

* Tenemos un array en una variable `libros` con libros para leer sobre Javascript.
* Usar la función `map` para crear un nuevo array donde cada titulo de los libros esté encerrado en una etiqueta `<li></li>`.
* Mostrar por consola el array nuevo, encerrándolo entre `<ul></ul>`

```js
const librosDeJS = [
  'JavaScript for Kids: A Playful Introduction to Programming',
  'Composing Software',
  'Eloquent JavaScript: A Modern Introduction to Programming',
  'JavaScript: The Good Parts',
  'Programming JavaScript Applications: Robust Web Architecture with Node, HTML5, and Moderns JS Libraries',
  'Effective JavaScript: 68 Specific Ways to Harness the Power of JavaScript',
  'JavaScript: The Definitive Guide',
  'You Don’t Know JS',
  'JavaScript Allongé: The Six Edition'
];

// codear acá la solución del ejercicio



// el resultado final debería ser
// <ul><li>JavaScript for Kids: A Playful Introduction to Programming</li><li>Composing Software</li><li>Eloquent JavaScript: A Modern Introduction to Programming</li><li>JavaScript: The Good Parts</li><li>Programming JavaScript Applications: Robust Web Architecture with Node, HTML5, and Moderns JS Libraries</li><li>Effective JavaScript: 68 Specific Ways to Harness the Power of JavaScript</li><li>JavaScript: The Definitive Guide</li><li>You Don’t Know JS</li><li>JavaScript Allongé: The Six Edition</li></ul>
```

### 5

* Tenemos un array en una variable `frases` con frases al azar.
* Usar la función `map` para crear un nuevo array que contenga la longitud de cada palabra.
* Mostrar por consola el array original y el nuevo.

```js
const frases = ['Labore sea dolor.', 'Justo rebum dolor.', 'Stet lorem amet.'];

// codear acá la solución del ejercicio


console.log(frases); // ['Labore sea dolor.', 'Justo rebum dolor.', 'Stet lorem amet.']
console.log(longitudes); // [ 17, 18, 16 ]
```

### 6

* Tenemos un array en una variable `playlist` con una lista de canciones de un disco.
* Usar la función `map` para agregar a cada título de la canción el número de posición en la que está dentro del array.

```js
const playlist = ['Everlong', 'The Pretender', 'Learn to Fly'];

/// completá acá el código



// RESULTADO ESPERADO
// [ '0 - Everlong', '1 - The Pretender', '2 - Learn to Fly' ]
```

### 7

* Tenemos un array en una variable `costos` con números que representan costos de diferentes productos.
* Completar el siguiente código para llegar al resultado esperado
* A un costo primero se le agrega la ganancia y después el IVA

```js
const costos = [ 12.5, 56, 98, 45.75 ];

const agregarIVA = function (costo) {
  return costo * 1.21;
}

const sumarGanancia = function (costo) {
  return costo * 1.5;
}

// codear acá la solución del ejercicio


console.log(preciosFinales);
// deberia mostrar
// [ 22.6875, 101.64, 177.87, 83.03625 ]
```

### 8

* Tenemos un array en una variable `costos` con números que representan costos de diferentes productos.
* También tenemos un array en una variable `productos` con los nombres de cada producto.
* Completar el siguiente código para llegar al resultado esperado
* A un costo primero se le agrega la ganancia y después el IVA
* El nombre de un producto en una posición, se corresponde con el precio que está en la misma posición. Por ejemplo: el producto que está en la posición **1** tiene un costo igual al elemento en la posición **1** del array `costos`

```js
const productos = [ 'celular', 'notebook', 'monitor' ];
const costos = [ 12.5, 56, 98 ];

const agregarIVA = function (costo) {
  return costo * 1.21;
}

const sumarGanancia = function (costo) {
  return costo * 1.5;
}

// codear acá la solución del ejercicio


console.log(preciosFinales);
// deberia mostrar
// [ "celular 22.6875", "notebook 101.64", "monitor 177.87" ]
```
