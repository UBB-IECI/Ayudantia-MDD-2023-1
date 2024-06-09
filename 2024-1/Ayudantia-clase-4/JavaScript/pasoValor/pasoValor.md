
## Paso por valor

El paso por valor en JavaScript es en donde se realiza la asignación de un valor y no se apunta en si a la memoria.

### Ejemplo 1

```js
let x = 1;
let y = 'Hola';
let z = null;
```

![pasoValor.png](../../images/pasoValor.png)

### Ejemplo 2

```js
// Creación variables con valores de tipo number, string y null.
let x = 1;
let y = 'Hola';
let z = null;

// Pasamos el valor de las variables ya creadas a unas nuevas.
let a = x;
let b = y;
let c = z;

console.log(x, y, z, a, b, c); // 1 'Hola' null 1 'Hola' null

// Se les asigna nuevos valores a las variables.
a = 12;
b = 'Adios';
c = undefined;

console.log(x,y,z,a,b,c); // 1 'Hola' null 12 'Adios' undefined
```

![pasoValor2.png](../../images/pasoValor2.png)