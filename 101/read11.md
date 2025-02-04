# READ 11: Introducción al DOM

## Reflexiona y debate

A continuación se muestra una colección de recursos que describen los temas de la clase.

Revisa estos recursos y agrega una nueva entrada a este foro que resuma los temas que aprendiste como si estuvieras presentando el material a un amigo (sin conocimientos técnicos) interesado en aprender sobre esto.

## Lectura

La lectura de este artículo es obligatoria.

- [Introducción al DOM](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model/Introduction)

## Recursos Extra

- [Manejo del DOM JS](https://developer.mozilla.org/es/docs/Web/API/Document_Object_Model)

## Responde

1. **¿Qué es el DOM?**  
   El DOM (Document Object Model) es una representación en forma de árbol de los elementos de un documento HTML o XML. Permite a los programas (como JavaScript) acceder, modificar y manipular el contenido, la estructura y el estilo de una página web de manera dinámica.

2. **Describe brevemente la relación entre el DOM y JavaScript.**  
   JavaScript utiliza el DOM para interactuar con los elementos de una página web. A través del DOM, JavaScript puede acceder a los elementos HTML, modificar su contenido, cambiar estilos, agregar o eliminar elementos, y responder a eventos del usuario (como clics o tecleos). El DOM actúa como un puente entre el código JavaScript y la estructura HTML de la página.

3. **¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?**  
   Para seleccionar un elemento del DOM por su ID, se utiliza el método `document.getElementById()`. Este método toma como argumento el ID del elemento y devuelve el elemento correspondiente.

   Ejemplo:
   ```javascript
   let elemento = document.getElementById("miElemento");
   ```

4. **¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría?**
    Para cambiar el color de fondo de un elemento en el DOM, se puede acceder a la propiedad **`style.backgroundColor`** del elemento seleccionado.

    Ejemplo:
    ```javascript
    let elemento = document.getElementById("miElemento");
    elemento.style.backgroundColor = "blue";
    ```

**Instrucciones de Envío**

1. Agrega las preguntas y respuestas de esta actividad a tu archivo **`read11.md`** de tu repositorio **`reading-notes`**. Recuerda seguir utilizando Markdown y tu mejor criterio para estructurar tu contenido.

    💡 Para insertar un bloque de código en Markdown, utiliza el carácter “backtick” (`) 3 veces para indicar la apertura del bloque, y 3 veces al final del bloque.

2. Agrega en la Respuesta a esta actividad:

    - El link a tu página nueva publicada.

    - Y también, las respuestas que desarrollaste.

3. Una vez enviada tu respuesta, revisa las respuestas de tus compañeros. Escoge la respuesta que te haya parecido más útil y agrégale un comentario positivo (recuerda que esta es una actividad de foro).