# Apuntes de Github/Markdown/HTML
## Indice:
1. [Github](#GITHUB)
2. [Markdown](#Markdown)
3. [HTML](#HTML)

# GITHUB

## Comandos básicos de Git

1. **Creación de repositorios:**
   - Crearemos los repositorios desde la página web.
   - Como vemos en la img, dentro de nuestro perfil de repositorios, pulsaremos en "New":
   ![KTM IMG](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/newrepo.png "img de crear repo")
   - Tras pulsar ahí, nos pedirá toda la info que vemos en la siguiente imagen, y la rellenaremos a nuestro gusto, *es muy importante que si queremos que la gente lo pueda ver, lo marquemos como público*
   ![KTM IMG](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/infonewrepo.png "img info repo")

2. **Clonar un repositorio:**
   - Utilizaremos la orden: `git clone <link del repositorio>`.

3. **Inicializar un repositorio:**
   - Utilizaremos: `git init`.

4. **Cambiar la rama:**
   - Con `git branch -M` podremos cambiar la rama.

5. **Ver las ramas del repositorio:**
   - Utilizaremos: `git branch`.

6. **Añadir actualizaciones al área intermedia:**
   - Con `git add .` subiremos todas las actualizaciones al área intermedia.

7. **Guardar los cambios en un commit:**
   - Con `git commit -m "info commit"` guardaremos los cambios del área intermedia en un commit para después poder subirlos.

8. **Subir el commit:**
   - Utilizaremos: `git push origin main`.

## Publicar en GitHub Pages

1. En nuestro repositorio de GitHub, iremos a la pestaña **Settings**.
2. Nos desplazaremos hasta la sección **Pages**.
3. En **Source**, seleccionaremos la rama que contenga lo que queremos publicar (main).
4. Guardaremos los cambios.

# Markdown
## Segundo nivel encabezado
### Tercer nivel encabezado
#### Cuarto nivel encabezado
##### Quinto nivel encabezado
###### Sexto nivel encabezado
markdown clase 1
tunning de palabras: _cursiva_ *cursiva* **negrita** **_cursinegra_**

1. Primer punto de la lista
    1. Primer elemento sublista
    2. Segundo

2. Segundo punto lista
    * Primer elemento sublista 2
    - segundo
3. Tercer punto lista

* Primer punto lista desordenada
- Segundo punto lista desordenada
+ Tercer punto lista desordenada

**Cómo mostrar código en un repositorio**

``` html
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de ejemplo</title>
</head>
<body>

    <h1>¡Bienvenido a mi página web!</h1>

    <p>Esta es una página web sencilla generada con HTML. Aquí puedes ver un botón interactivo y una lista de elementos.</p>

    <button onclick="alert('¡Hola! Has hecho clic en el botón.')">Haz clic aquí</button>

    <h2>Lista de cosas por hacer:</h2>
    <ul>
        <li>Estudiar HTML</li>
        <li>Aprender CSS</li>
        <li>Practicar JavaScript</li>
        <li>Crear una página web</li>
    </ul>

</body>
</html>

```
### Como poner un link

[Web J23](https://www.fje.edu/ca/jesuites-bellvitge "popup")

### Como poner una imagen

![KTM IMG](https://raw.githubusercontent.com/davidvazquez33/Apuntes_Git_Markdown_HTML/main/img/ktm.png "PopUP")

### Como Hacer una tabla:


| Titulo 1 | Titulo 2 | Titulo 3 |
|--------------|:-------------:|-------------:|
|Izquierda|Medio|Derecha|

# HTML

**HTML (HyperText Markup Language)** es el lenguaje estándar utilizado para crear y estructurar el contenido en la web.  
Actúa como el esqueleto de una página web, permitiendo organizar elementos como texto, imágenes, enlaces, tablas y formularios mediante el uso de etiquetas específicas.  
Estas etiquetas no se ven directamente en la página, pero definen cómo se presenta y organiza la información para el usuario.  

## Etiquetas

Las etiquetas de HTML son comandos que delimitan el inicio y el final de un elemento en una página web, como `<p>` para párrafos o `<img>` para imágenes.  
Estas etiquetas definen la estructura y el tipo de contenido.

## Atributos

Los atributos son propiedades añadidas a las etiquetas que aportan información adicional o modifican su comportamiento, como `src` para definir la fuente de una imagen o `href` para especificar un enlace.

## Ejemplo de estructura básica de HTML5

```html
<!DOCTYPE html>             <!-- Indica que es HTML5 -->
<html lang="en">            <!-- Contenedor principal del documento -->
<head>                      <!-- Datos como el título de página, links a CSS… -->
    <meta charset="UTF-8">  <!-- Define algunos metadatos -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Estructura HTML</title>  <!-- Título de página -->
</head>
<body>                      <!-- Contenido visible de la web -->
    
</body>
</html>
```

## Legibilidad y Organización del Código

## Legibilidad
La **legibilidad** se refiere a la claridad con la que está escrito el código.  
Es muy importante porque casi nunca trabajamos solos, por lo que el código debe ser comprensible para los demás, no solo para nosotros.

### ¿Cómo hacer el código más legible?
1. **Comentándolo:**  
   - En el caso de HTML, se utiliza: `<!-- comentario -->`.

2. **Indentación del código:**  
   - Utilizar espacios o tabulaciones (TAB) para estructurar el código correctamente.

3. **Organización de los archivos con nombres representativos:**  
   - Ejemplo: Si tenemos una imagen de una sandía, podemos nombrarla `sandia.png` en lugar de nombres genéricos como `jjfaj.png` o `img.png`.

4. **Estructura de carpetas óptima:**  
   - Es recomendable organizar los archivos en carpetas. Ejemplo:

![Estructura carpetas](https://raw.githubusercontent.com/davidvazquez33/Apuntes_Git_Markdown_HTML/main/img/EstructuraCarpetas.png "Ejemplo de Estructura carpetas")

## Tipos de etiquetas HTML

## En bloque
Necesitan una línea nueva para ejecutarse, ejemplos:
- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>`
- `<p></p>`
- `<ul>`
- `<ol>`
- `<li>`

## En línea
Se pueden ejecutar en la misma línea que un bloque, ejemplos:
- `<a>`
- `<strong>`
- `<em>`

## Imágenes

La etiqueta `<img>` se utiliza para insertar imágenes en una página web. Es una etiqueta vacía, lo que significa que no tiene una etiqueta de cierre (`</img>`). Se le pueden añadir diferentes atributos.

## Atributos principales de `<img>`:
- **`src`**: Especifica la ruta de la imagen que se desea mostrar. Puede ser:
  - **Ruta absoluta**: Enlace completo (ejemplo: `https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/EstructuraCarpetas.png`).
  - **Ruta relativa**: Ruta del archivo dentro del mismo proyecto (ejemplo: `../img/img1`).
- **`alt`**: Proporciona texto alternativo que se muestra si la imagen no puede cargarse.
- **Con `width` y `height`**: Podemos darle el tamaño que queramos a la imagen.

## Links

Para poner links (de manera básica) utilizamos la etiqueta `<a>`, junto con el atributo `href`.

## Ejemplo:

```html
<a href="https://github.com/davidvazquez33">Mi Github</a>
```

# Formularios

Los formularios en HTML son elementos interactivos que permiten recopilar datos del usuario, como texto, opciones o archivos, y enviarlos para su procesamiento. Se definen con la etiqueta `<form>` y pueden incluir campos como `<input>`, menús desplegables, botones y más.

## Etiquetas de formularios:

- **`<form>`**: La utilizamos para comenzar con el formulario.

- **`<input>`**: Para recibir datos, sus atributos más usados son:
  - **`text`**: Para introducir texto simple.
  - **`password`**: Para que sea como texto "ocultado", ya que es una contraseña.
  - **`checkbox`**: Para hacer una casilla de verificación.
  - **`placeholder`**: Texto informativo dentro del campo cuando está vacío.

- **`<select>`**: Para definir un menú desplegable.

- **`<button>`**: Para definir un botón.

- **`<option>`**: Para definir una a una las opciones del menú.

- **`<fieldset>`**: Para agrupar diferentes elementos de un formulario.

- **`<legend>`**: Para poner un título de grupo.

- **`<textarea>`**: Para definir un área de texto. Atributos:
  - **`rows`**: Filas visibles.
  - **`cols`**: Columnas visibles.

  ## Ejemplo de formulario:

  ```html
  <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form action="recepcion.php" method="GET">
        <label>Nombre:</label>
        <input type="text" name="nombre" placeholder="Introduce tu nombre"><br><br>
        <label>Passwd:</label>
        <input type="password" name="password" placeholder="Introduce tu contraseña"><br>
    <fieldset>
        <legend>Idioma</legend>
        <label for="castellano">Castellano:</label>
        <input type="radio" name="idioma" value="castellano" id="castellano">
        <label for="catalan">Catalan:</label>
        <input type="radio" name="idioma" value="catalan" id="catalan">
        <label for="ingles">ingles:</label>
        <input type="radio" name="idioma" value="ingles" id="ingles">
    </fieldset>
    <label for="obs">Observaciones:</label><br>
    <textarea name="observaciones" id="obs" cols="80" rows="4" placeholder="introduce observaciones"></textarea>
    <br><br>
    <select id="ciudad" name="ciudad">
        <option value="">Seleccione una ciudad</option>
        <option value="Barcelona">Barcelona</option>
        <option value="Madrid">Madrid</option>
        <option value="Valencia">Valencia</option>
        <option value="Sevilla">Sevilla</option>
        <option value="Murcia">Murcia</option>
    </select>

# Validación HTML

## W3C HTML VALIDATOR

Un validador web permite comprobar si el código de una página en formatos como HTML y CSS es correcto, ayudando a detectar errores y enlaces inactivos, y mejorando la sintáxis a pesar de que funcione.

### Métodos de validación  

Existen tres formas principales de realizar la validación:  

1. **Mediante la URL**: Se introduce la dirección web de la página para analizar su contenido.  
2. **Subiendo un archivo**: Se carga directamente el documento que contiene el código.  
3. **Copiando y pegando el código**: Se inserta manualmente el código en el validador para su revisión.  

### Como se ven los errores:

En la imagen, podemos ver como este validador nos marca los errores, sinceramente, si tienes el inglés dominado, será muy facil arreglar los fallos.

![KTM IMG](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/erroresW3C.png "PopUP")


</body>
</html>





