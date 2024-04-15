
## Anatomía de una variable

En JavaScript, una variable es un contenedor que puede almacenar información. Esta información puede cambiar durante la ejecución del programa. Las variables se utilizan para almacenar y manipular datos durante la ejecución del código.

### Tipos de variables

- `let`: Se utiliza para declarar una variable que puede ser cambiada después de su inicialización.
- `const`: Se utiliza para declarar una variable cuyo valor no puede ser cambiado después de su inicialización.	
- `var`: Es otro tipo de declaración de variable, sin embargo, su uso no es recomendable en la actualidad debido a sus peculiaridades con el alcance (scope) y hoisting. A diferencia de `let` y `const`, una variable declarada con `var` puede ser re-declarada.

### Ejemplos

```js
var nombre = "Diego";
let apellido = "Salazar";
const edad = 20;
```

### Recomendaciones

- Usar `let` en lugar de `var` para declarar variables.
- Usar `const` para declarar variables que no van a cambiar su valor.
- Usar `nombres descriptivos` para las variables.
- Usar nombres con [camelCase](https://developer.mozilla.org/en-US/docs/Glossary/Camel_case) para las variables.