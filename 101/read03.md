# ¿Cuál es el propósito de CSS?

**CSS** (Cascading Style Sheets) o en español **Hojas de Estilos en Cascada**, es un lenguaje diseñado para controlar los estilos y presentación de los elementos de HTML en una página web.

Su principal propósito es **distinguir la estructura del contenido HTML de su apariencia**, permitiendo personalizar:

- Tamaño
- Colores
- Espaciado
- Fuentes
- Disposición

Esto mejora la experiencia visual del usuario, además de facilitar el mantenimiento del diseño.

---

# ¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?

Para poder explicar de una manera que todos entiendan la responsabilidad de **HTML** vs **CSS**, hagamos de idea que:

- **HTML** es como la **estructura de una casa**, donde se definen las paredes, puertas, ventanas, etc.
- **CSS** es la **decoración interior y exterior**, donde se decide el color de las paredes, el tipo de muebles y la distribución de los espacios.

# ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
Según lo analizado en el artículo [Cómo agregar CSS](https://www.w3schools.com/css/css_howto.asp) a un sitio externo., existen 3 maneras de insertar CSS en nuestro proyecto.

1. **Externa**: Vinculando un archivo CSS separado con una etiqueta ``<link>`` en el ``<head>`` del documento HTML, como ``<link rel="stylesheet" href="styles.css">``. Es importante recalcar que una hoja de estilo externa se puede escribir en cualquier editor de texto y debe guardarse con una extensión **".css"**.
2. **Interna**: Escribiendo el CSS dentro de una etiqueta ``<style>`` en el ``<head>`` del documento HTML. Es importante indicar que se puede utilizar una hoja de estilo interna si una sola página HTML tiene un estilo único.
3. **En Línea**: Usando el atributo style directamente dentro de las etiquetas HTML, como ``<p style="color:red;">Texto</p>``. Esta manera se tiene que usar con moderación dado a que un estilo en línea se pierde de muchas de las ventajas de una hoja de estilo.

# Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos ``<p>``.
Para aplicar el color rojo a todos los elementos ``<p>``, se puede aplicar la siguiente regla:
```
p {
	color : red;
}
```
Esta regla de CSS se puede usar en cualquier archivo CSS ya sea de manera externa, interna o en línea.

# READ 03: Introducción a CSS

## Reflexiona y debate

A continuación se muestra una colección de recursos que describen los temas de la clase.

Revisa estos recursos y agrega una nueva entrada a este foro que resuma los temas que aprendiste como si estuvieras presentando el material a un amigo (sin conocimientos técnicos) interesado en aprender sobre esto.

## Lectura

La lectura de este artículo es obligatoria.

- **Qué es CSS**

## Practica

- **Cómo insertar CSS**

## Recursos Extra

- [Referencia CSS](https://developer.mozilla.org/es/docs/Web/CSS/Reference)
- [Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/) (Conversa sobre este artículo con tus instructores).

## Responde

1. **¿Cuál es el propósito de CSS?**
   - El propósito de CSS (Cascading Style Sheets) es controlar la presentación y el diseño de una página web. Permite definir estilos como colores, fuentes, márgenes, tamaños y posiciones, separando así el contenido (HTML) de su apariencia visual.

2. **¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?**
   - Una analogía no técnica sería comparar HTML con la estructura de una casa (paredes, techos, puertas) y CSS con la decoración y el estilo de la casa (colores de las paredes, muebles, iluminación). HTML define "qué hay" y CSS define "cómo se ve".

3. **¿Cuáles son las tres formas de insertar CSS en tu proyecto?**
   - Las tres formas de insertar CSS son:
     1. **CSS interno**: Usando la etiqueta `<style>` dentro del `<head>` del documento HTML.
     2. **CSS externo**: Enlazando un archivo CSS externo usando la etiqueta `<link>` en el `<head>` del documento HTML.
     3. **CSS en línea**: Aplicando estilos directamente en un elemento HTML usando el atributo `style`.

4. **Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`.**
   ```css
   p {
       color: red;
   }