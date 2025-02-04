# READ 10: Arreglos y Control de Flujo

## Reflexiona y practica

A continuación se muestra una colección de recursos que describen los temas de la clase. Revisa estos recursos y practica la sintaxis de este nuevo lenguaje en línea. Al final, contestarás unas preguntas en referencia a lo que has aprendido.

## Lectura

La lectura de este artículo es obligatoria.

- [Control de Flujo](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)

## Recursos Extra

- [Funciones](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Functions)
- [Bucles](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Loops_and_iteration)  
  Concéntrate únicamente en los bucles `for Statement` y `while Statement`.
- [Arreglos](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array)

## Practica

- [Funciones](https://www.w3schools.com/js/js_functions.asp)
- [Arreglos](https://www.w3schools.com/js/js_arrays.asp)
- [Bucle For](https://www.w3schools.com/js/js_loop_for.asp)

## Responde

1. **¿Qué es “Control Flow” (Control de Flujo)?**  
   El Control de Flujo se refiere al orden en el que se ejecutan las instrucciones en un programa. Esto incluye estructuras como condicionales (`if`, `else`, `switch`) y bucles (`for`, `while`), que permiten controlar cómo y cuándo se ejecuta el código.

2. **¿Qué es una “function” (Función) de JavaScript?**  
   Una función en JavaScript es un bloque de código reutilizable que realiza una tarea específica. Se define con la palabra clave `function`, seguida de un nombre, parámetros (opcionales) y un cuerpo de código entre llaves `{}`. Las funciones pueden devolver un valor usando `return`.

   Ejemplo:

   ```javascript
   function sumar(a, b) {
     return a + b;
   }
   ```
3. **¿Cuántas veces se ejecutará un bucle “while”?**
    Un bucle **`while`** se ejecutará mientras la condición especificada sea verdadera (**`true`**). Si la condición nunca se vuelve falsa, el bucle se ejecutará indefinidamente (bucle infinito). Por ejemplo:

    ```javascript
    let i = 0;
    while (i < 5) {
        console.log(i);
        i++;
    }
    ```
    En este caso, el bucle se ejecutará 5 veces.

4. **¿Qué método usarías para agregar un elemento al final de un array y cómo se utiliza?**
    Para agregar un elemento al final de un array, se utiliza el método **`push()`**. Este método añade el elemento especificado al final del array y devuelve la nueva longitud del array.

    Ejemplo:

    ```javascript
    let frutas = ["manzana", "banana"];
    frutas.push("naranja"); // ["manzana", "banana", "naranja"]
    ```

**Instrucciones de Envío**

1. Agrega las preguntas y respuestas de esta actividad a tu archivo **`read10.md`** de tu repositorio **`reading-notes`**. Recuerda seguir utilizando Markdown y tu mejor criterio para estructurar el contenido.

2. Agrega en la Respuesta a esta actividad:

    - El link a tu nueva página publicada.

    - Y también, las respuestas que desarrollaste.

3. Una vez enviada tu respuesta, revisa las respuestas de tus compañeros. Escoge la que te haya parecido más útil y agrégale un comentario positivo (recuerda que esta es una actividad de foro).