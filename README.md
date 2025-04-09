# Apuntes de Github/Markdown/HTML
## Indice:
1. [Github](#GITHUB)
2. [Markdown](#Markdown)
3. [HTML](#HTML)
4. [CSS](#CSS)

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

Para insertar un enlace en Markdown, utilizamos la siguiente sintaxis:  
```markdown
[Texto del enlace](URL "Texto emergente opcional")
```
- **Texto del enlace**: Es el texto que se mostrará como enlace.  
- **URL**: Es la dirección a la que apunta el enlace.  
- **Texto emergente opcional**: Es un texto que aparece al pasar el ratón sobre el enlace (opcional).  

Ejemplo:  
```markdown
[Web J23](https://www.fje.edu/ca/jesuites-bellvitge "popup")
```
Resultado:  
[Web J23](https://www.fje.edu/ca/jesuites-bellvitge "popup")

### Como poner una imagen

Para insertar una imagen en Markdown, utilizamos la siguiente sintaxis:  
```markdown
![Texto alternativo](URL "Texto emergente opcional")
```
- **Texto alternativo**: Es el texto que se mostrará si la imagen no se carga.  
- **URL**: Es la dirección de la imagen.  
- **Texto emergente opcional**: Es un texto que aparece al pasar el ratón sobre la imagen (opcional).  

Ejemplo:  
```markdown
![KTM IMG](https://raw.githubusercontent.com/davidvazquez33/Apuntes_Git_Markdown_HTML/main/img/ktm.png "PopUP")
```
Resultado:  
![KTM IMG](https://raw.githubusercontent.com/davidvazquez33/Apuntes_Git_Markdown_HTML/main/img/ktm.png "PopUP")

### Como Hacer una tabla:

Para crear una tabla en Markdown, utilizamos la siguiente sintaxis:  
```markdown
| Columna 1 | Columna 2 | Columna 3 |
|-----------|:---------:|----------:|
| Alineada a la izquierda | Centrada | Alineada a la derecha |
```
- Los guiones (`-`) debajo de los encabezados definen la tabla.  
- Los dos puntos (`:`) definen la alineación:  
  - `:---` para alineación a la izquierda.  
  - `:---:` para alineación centrada.  
  - `---:` para alineación a la derecha.  

Ejemplo:  
```markdown
| Titulo 1 | Titulo 2 | Titulo 3 |
|----------|:--------:|---------:|
| Izquierda | Medio | Derecha |
```
Resultado:  
| Titulo 1 | Titulo 2 | Titulo 3 |
|----------|:--------:|---------:|
| Izquierda | Medio | Derecha |

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

## Métodos de envío: POST y GET

Cuando enviamos datos desde un formulario HTML, podemos usar los métodos `POST` o `GET` especificados en el atributo `method` de la etiqueta `<form>`:

1. **GET**:  
   - Envía los datos como parte de la URL, lo que los hace visibles en la barra de direcciones del navegador.  
   - Es útil para solicitudes donde no se maneja información sensible, como búsquedas o filtros.  
   - Ejemplo:
     ```html
     <form action="procesar.php" method="GET">
         <input type="text" name="nombre" placeholder="Introduce tu nombre">
         <button type="submit">Enviar</button>
     </form>
     ```
     Resultado en la URL: `https://example.com/procesar.php?nombre=Juan`.

2. **POST**:  
   - Envía los datos en el cuerpo de la solicitud HTTP, lo que los hace invisibles en la URL.  
   - Es más seguro y se utiliza para manejar información sensible, como contraseñas o datos personales.  
   - Ejemplo:
     ```html
     <form action="procesar.php" method="POST">
         <input type="password" name="password" placeholder="Introduce tu contraseña">
         <button type="submit">Enviar</button>
     </form>
     ```

**Diferencias clave**:
- **GET** es más rápido y adecuado para solicitudes idempotentes (que no cambian el estado del servidor).
- **POST** es más seguro y adecuado para enviar grandes cantidades de datos o información sensible.

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

# CSS

**CSS (Cascading Style Sheets)** es el lenguaje utilizado para describir la presentación de un documento HTML. Permite controlar el diseño, colores, fuentes y disposición de los elementos en una página web.

## ¿Por qué usar CSS?

CSS separa el contenido (HTML) de la presentación, lo que facilita el mantenimiento y mejora la experiencia del usuario. Además, permite crear diseños responsivos y atractivos.

![CSS LOGO](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/css.png "Logo css")

### Tipos de CSS

1. **CSS en línea**: Se aplica directamente en la etiqueta HTML usando el atributo `style`.
   ```html
   <p style="color: blue; font-size: 16px;">Texto en azul</p>
   ```

2. **CSS interno**: Se incluye dentro de una etiqueta `<style>` en el `<head>` del documento.
   ```html
   <style>
       p {
           color: red;
           font-size: 18px;
       }
   </style>
   ```

3. **CSS externo**: Se guarda en un archivo `.css` separado y se enlaza al HTML con `<link>`.
   ```html
   <link rel="stylesheet" href="styles.css">
   ```

### Selectores básicos

- **Selector de etiqueta**: Aplica estilos a todas las etiquetas de un tipo, hay de p, body...
  ```css
  p {
      color: green;
  }
  ```

- **Selector de clase**: Se aplica a elementos con una clase específica.
  ```css
  .miClase {
      font-weight: bold;
  }
  ```

- **Selector de ID**: Se aplica a un elemento con un ID único.
  ```css
  #miID {
      text-align: center;
  }
  ```

  ### Propiedades comunes

1. **Colores y fondos**:
   ```css
   body {
       background-color: #f0f0f0;
       color: #333;
   }
   ```

2. **Fuentes y texto**:
   ```css
   h1 {
       font-family: Arial, sans-serif;
       font-size: 24px;
       text-transform: uppercase;
   }
   ```

3. **Espaciado y bordes**:
   ```css
   div {
       margin: 10px;
       padding: 15px;
       border: 1px solid #ccc;
   }
   ```

4. **Sombra y efectos**:
   ```css
   box {
       box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5); /* Sombra de caja */
       text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3); /* Sombra de texto */
   }
   ```

5. **Transiciones y animaciones (hover)**:
   ```css
   button {
       background-color: #007bff;
       color: white;
       transition: background-color 0.3s ease; /* Transición suave */
   }

   button:hover {
       background-color: #0056b3; /* Cambia el color al pasar el ratón */
   }
   ```

6. **Decoración y estilo de enlaces**:
   ```css
   a {
       text-decoration: none; /* Quitar subrayado */
       color: blue; /* Color del enlace */
   }

   a:hover {
       text-decoration: underline; /* Subrayado al pasar el ratón */
   }
   ```

7. **Curvatura y bordes redondeados**:
   ```css
   button {
       border-radius: 10px; /* Bordes redondeados */
       border: 2px solid #000; /* Borde sólido */
   }
   ```

### Diseño responsivo

El diseño responsivo permite que una página web se adapte a diferentes tamaños de pantalla, mejorando la experiencia del usuario en dispositivos como móviles, tablets y ordenadores. Para lograrlo, se pueden utilizar:

1. **Unidades relativas**:  
   En lugar de usar unidades fijas como píxeles (`px`), se recomienda usar unidades relativas como:
   - **Porcentajes (`%`)**: Ajustan el tamaño en relación al contenedor padre.
   - **Viewport Height (`vh`) y Viewport Width (`vw`)**: Ajustan el tamaño en función del alto o ancho de la ventana del navegador.
   ```css
   body {
       font-size: 2vw; /* Tamaño de fuente relativo al ancho de la ventana */
   }

   div {
       width: 50%; /* Ocupa el 50% del ancho del contenedor */
       height: 50vh; /* Ocupa el 50% de la altura de la ventana */
   }
   ```

2. **Media queries**:  
   Permiten aplicar estilos específicos según el tamaño de la pantalla. Esto es útil para realizar **saltos de página**, que son puntos donde el diseño cambia para adaptarse mejor al dispositivo. Por ejemplo:
   ```css
   @media (max-width: 768px) {
       body {
           font-size: 14px; /* Cambia el tamaño de fuente en pantallas pequeñas */
       }
   }

   @media (min-width: 769px) and (max-width: 1200px) {
       body {
           font-size: 16px; /* Ajuste para pantallas medianas */
       }
   }
   ```
   En este ejemplo, se define un salto de página en 768px, donde el diseño cambia para pantallas más pequeñas, y otro entre 769px y 1200px para pantallas medianas.

Usar estas técnicas asegura que el diseño sea flexible y se vea bien en cualquier dispositivo.

![Responsive IMG](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/responsive.jpeg "Responsive IMG")

### Introducción a Bootstrap

**Bootstrap** es un framework CSS de código abierto que facilita la creación de diseños web modernos, responsivos y consistentes. Proporciona una amplia variedad de componentes predefinidos, como botones, tablas, formularios y sliders, además de un sistema de grillas para organizar el contenido de manera flexible.

#### ¿Por qué usar Bootstrap?

1. **Diseño responsivo**: Bootstrap utiliza un sistema de grillas que permite adaptar el diseño a diferentes tamaños de pantalla.
2. **Componentes predefinidos**: Incluye botones, tarjetas, tablas, sliders y más, listos para usar.
3. **Personalización**: Permite modificar estilos mediante clases o archivos CSS personalizados.
4. **Compatibilidad**: Funciona en todos los navegadores modernos.

#### Ejemplo básico con Bootstrap:

1. Enlaza Bootstrap en tu HTML:
   ```html
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
   ```

2. Usa clases predefinidas:
   ```html
   <div class="container">
       <h1 class="text-center text-primary">Bienvenido</h1>
       <button class="btn btn-success">Haz clic aquí</button>
   </div>
   ```

#### Ejemplos de componentes útiles de Bootstrap:

- **Botones**:  
  Bootstrap ofrece botones con diferentes estilos y colores. Puedes personalizarlos con clases como `btn-primary`, `btn-danger`, etc.
  ```html
  <button class="btn btn-primary">Primario</button>
  <button class="btn btn-secondary">Secundario</button>
  <button class="btn btn-success">Éxito</button>
  <button class="btn btn-danger">Peligro</button>
  <button class="btn btn-warning">Advertencia</button>
  <button class="btn btn-info">Información</button>
  ```

- **Tablas**:  
  Las tablas en Bootstrap son fáciles de estilizar con la clase `table`. Puedes añadir clases como `table-striped` para filas alternadas o `table-hover` para resaltar filas al pasar el ratón.
  ```html
  <table class="table table-striped table-hover">
      <thead class="table-dark">
          <tr>
              <th>#</th>
              <th>Nombre</th>
              <th>Edad</th>
              <th>Ciudad</th>
          </tr>
      </thead>
      <tbody>
          <tr>
              <td>1</td>
              <td>Juan</td>
              <td>25</td>
              <td>Barcelona</td>
          </tr>
          <tr>
              <td>2</td>
              <td>María</td>
              <td>30</td>
              <td>Madrid</td>
          </tr>
          <tr>
              <td>3</td>
              <td>Carlos</td>
              <td>28</td>
              <td>Valencia</td>
          </tr>
      </tbody>
  </table>
  ```

- **Sliders (Carruseles)**:  
  Bootstrap incluye un componente de carrusel para mostrar imágenes o contenido de manera interactiva.
  ```html
  <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="0" class="active" aria-current="true"></button>
          <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="1"></button>
          <button type="button" data-bs-target="#carouselExample" data-bs-slide-to="2"></button>
      </div>
      <div class="carousel-inner">
          <div class="carousel-item active">
              <img src="img/slide1.jpg" class="d-block w-100" alt="Slide 1">
          </div>
          <div class="carousel-item">
              <img src="img/slide2.jpg" class="d-block w-100" alt="Slide 2">
          </div>
          <div class="carousel-item">
              <img src="img/slide3.jpg" class="d-block w-100" alt="Slide 3">
          </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Anterior</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Siguiente</span>
      </button>
  </div>
  ```

#### Con / sin bootstrap
**En las imagenes vemos como simplemete con implementar bootstrap, la página cambia completamente, ya que pasa de ser plana sin estilos a tener estilos, estructuras, animaciones...**

*SIN Bootstrap*
![Sin Bootstrap](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/sin_boostrap.png "Sin Bootstrap")

*CON Bootstrap*
![Con Bootstrap](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/con_boostrap.png "Con Bootstrap")

