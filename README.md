# aprendizajemarkdown
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

[Web J23](https://www.fje.edu/ca/jesuites-bellvitge "popup")

### Como poner una imagen

![KTM IMG](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/ktm.png "PopUP")

### Como Hacer una tabla:


| Titulo 1 | Titulo 2 | Titulo 3 |
|--------------|:-------------:|-------------:|
|Izquierda|Medio|Derecha|

# APUNTES GITHUB

# Comandos básicos de Git

1. **Creación de repositorios:**
   - Crearemos los repositorios desde la página web.

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

# HTML

**HTML (HyperText Markup Language)** es el lenguaje estándar utilizado para crear y estructurar el contenido en la web.  
Actúa como el esqueleto de una página web, permitiendo organizar elementos como texto, imágenes, enlaces, tablas y formularios mediante el uso de etiquetas específicas.  
Estas etiquetas no se ven directamente en la página, pero definen cómo se presenta y organiza la información para el usuario.  

## Etiquetas

Las etiquetas de HTML son comandos que delimitan el inicio y el final de un elemento en una página web, como `<p>` para párrafos o `<img>` para imágenes.  
Estas etiquetas definen la estructura y el tipo de contenido.

## Atributos

Los atributos son propiedades añadidas a las etiquetas que aportan información adicional o modifican su comportamiento, como `src` para definir la fuente de una imagen o `href` para especificar un enlace.

# Ejemplo de estructura básica de HTML5

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

# Legibilidad y Organización del Código

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

![Estructura carpetas](https://github.com/davidvazquez33/Apuntes_Git_Markdown_HTML/blob/main/img/EstructuraCarpetas.png "Ejemplo de Estructura carpetas")





