# READ 09: Introducción a Javascript

## Reflexiona y debate

A continuación se muestra una colección de recursos que describen los temas de la clase.

Revisa estos recursos y practica la sintaxis de este nuevo lenguaje en línea:

- **Operadores**
- **Condicionales**

Al final, contestarás unas preguntas en referencia a lo que has aprendido.

## Lectura

La lectura de este artículo es obligatoria.

- [Variables y tipos de datos de JS](#)

## Recursos Extra

- [Operadores en JS](#)
- [Operadores condicionales](#) (Conversa sobre este artículo con tus instructores).

## Responde

### 1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?

En JavaScript, los tipos de datos se dividen en dos categorías principales: **primitivos** y **objetos**.

- **Tipos primitivos**:

  - `string`: Cadenas de texto, como `"Hola"`.
  - `number`: Números, tanto enteros como decimales, como `42` o `3.14`.
  - `boolean`: Valores lógicos, `true` o `false`.
  - `null`: Representa la ausencia intencional de valor.
  - `undefined`: Indica que una variable no ha sido asignada.
  - `symbol` (ES6): Valores únicos e inmutables, útiles como identificadores.

- **Objetos**:
  - `object`: Estructuras de datos que contienen pares clave-valor, como `{ nombre: "Juan", edad: 30 }`.
  - `array`: Listas ordenadas de valores, como `[1, 2, 3]`.
  - `function`: Bloques de código reutilizables.

Los tipos primitivos son inmutables y se pasan por valor, mientras que los objetos son mutables y se pasan por referencia.

---

### 2. ¿Cómo se utilizan las estructuras condicionales `if` y `else` en JavaScript, y qué propósito cumplen dentro de un programa?

Las estructuras condicionales `if` y `else` permiten ejecutar bloques de código basados en condiciones lógicas.

- **`if`**: Evalúa una condición. Si es `true`, ejecuta el bloque de código asociado.

  ```javascript
  if (edad >= 18) {
    console.log("Eres mayor de edad.");
  }
  ```

- **`else`**: Se ejecuta si la condición del **`if`** es **`false`**.

  ```javascript
  if (edad >= 18) {
    console.log("Eres mayor de edad.");
  } else {
    console.log("Eres menor de edad.");
  }
  ```

- **`else if`**: Permite evaluar múltiples condiciones.

  ```javascript
  if (edad < 13) {
    console.log("Eres un niño.");
  } else if (edad < 18) {
    console.log("Eres un adolescente.");
  } else {
    console.log("Eres un adulto.");
  }
  ```
Estas estructuras son fundamentales para controlar el flujo de un programa, permitiendo tomar decisiones basadas en condiciones específicas.

---

### 3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos? ###

En JavaScript, los operadores se clasifican en varias categorías: 

1. Operadores aritmeticos:
    - **`+`** (suma), **`-`** (resta), **`*`** (multiplicación), **`/`** (división), **`%`** (módulo), **`**`** (exponenciación).
    - Ejemplo

    ```javascript
    let suma = 5 + 3; // 8
    let potencia = 2 ** 3; // 8
    ```
2. Operadores de comparación:
    - **`==`** (igualdad), **`===`** (igualdad estricta), **`!=`** (desigualdad), **`!==`** (desigualdad estricta), **`>`** (mayor que), **`<`** (menor que), **`>=`** (mayor o igual), **`<=`** (menor o igual).
    - Ejemplo:

    ```javascript
    if (edad === 18) {
        console.log("Tienes 18 años.");
    }
    ```
3. Operadores lógicos:
    - **`&&`** (AND), **`||`** (OR), **`!`** (NOT).
    - Ejemplo:

    ```javascript
    if (edad > 12 && edad < 20) {
        console.log("Eres un adolescente.");
    }
    ```

4. Operadores de asignación:
    - **`=`** (asignación), **`+=`** (suma y asignación), **`-=`** (resta y asignación), etc.
    - Ejemplo:

    ```javascript
    let contador = 0;
    contador += 1; // contador = 1
    ```
5. Otros operadores:
    - Operador ternario: **`condición ? valor1 : valor2`**.
    - Operador de tipo: **`typeof`**.

---

### 4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad? ###

En JavaScript, las variables se declaran usando **`var`**, **`let`** o **`const`**.

- **`var`**:
    - Alcance: Función (no bloque).
    - Reasignación: Sí.
    - Redeclaración: Sí.
    - Ejemplo:

    ```javascript
    var nombre = "Juan";
    nombre = "Pedro"; // Reasignación permitida
    ```
- **`let`**:
    - Alcance: Bloque.
    - Reasignación: Sí.
    - Redeclaración: No.
    - Ejemplo:

    ```javascript
    let edad = 25;
    edad = 26; // Reasignación permitida
    ```
- **`const`**:
    - Alcance: Bloque.
    - Reasignación: No.
    - Redeclaración: No.
    - Ejemplo:

    ```javascript
    const PI = 3.1416;
    // PI = 3.14; // Error: No se puede reasignar
    ```

---

 #### Diferencias clave: #### 

 - **`var`** tiene un alcance de función, mientras que **`let`** y **`const`** tienen alcance de bloque.

- **`const`** no permite reasignación, lo que lo hace ideal para valores constantes.

- **`let`** y **`const`** son preferibles sobre **`var`** debido a su comportamiento más predecible y seguro.
