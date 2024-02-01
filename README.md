# Asix_ApuntesM4_CeprianIker
## Primer repositorio GiftHub
*cursiva*  _cursiva_
**negrita**  __negrita__

**_negrita_**
Primer Repositorio GiftHub

* Lista

+ Elemento 1
+ Elemento 2

Lista desordenada 
1. Paso **1**
2. Paso **2**
..* Paso 1
..* Paso 2
3. Paso **3**

HUGO CALDA

XAVI CONDA

```html
<html>
  <head>
  </head>
</html>
```
[GOOGLE](http://www.google.com "Click Aqui")

![El Bicho](1527180943_971132_1527370360_noticia_normal.jpg "5 Champions")


| Titulo | Titulo 2 | Titulo 3 |
|--------|:---------:|----------:|
| Iker   | Ceprian  | Rodriguez |
| Jordi  | Sorribes | Marot     |
| Col 3  | esta alineada| Derecha |
| Col 2  | esta alineada| Centro |





HTML sirve para crear páginas web y tiene una estructura que incluye secciones como head y body, con etiquetas para introducir elementos. En la etiqueta de apertura se pueden agregar clases, por ejemplo:
```html
<div class="contenido-visible">Contenido</div>
```
Crear un documento HTML básico se logra con la siguiente estructura:
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="estilos.css">
    <meta name="keyboard" content="UTF-8">
    <title>Título de la Página</title>
</head>
<body>
    <!-- Etiquetas visibles de la página web -->
    <h1>Título</h1>
    <p>Párrafo de texto.</p>
    <!-- Etiquetas de bloque -->
    <ol>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
    </ol>
    <!-- Etiquetas de línea -->
    <a href="url-del-enlace">Enlace</a>
    <!-- Salto de línea -->
    <br>
    <!-- Comentario -->
    
    <!-- Este es un comentario -->

    <!-- Insertar imagen -->
    <img src="ruta-o-url-de-la-imagen" alt="Descripción de la imagen">
    <!-- Enlace a otro destino -->
    <a href="#id-en-la-misma-pagina">Enlace interno</a>
    <a href="url-del-enlace">Enlace externo</a>
    <!-- Cambiar icono de la página -->
    <link rel="icon" href="ruta-del-icono">
    <!-- Cambiar título de la página -->
    <title>Nuevo Título de la Página</title>
</body>
</html>
```
En CSS, se personaliza la página web, ya sea de forma interna o externa. Por ejemplo:
```css
/* CSS interno */
table {
    border: 1px solid red;
    color: red;
}

/* CSS externo */
h1 {
    color: red;
}
```
Para declarar un ID y enlazarlo, puedes hacerlo de la siguiente manera:
```html
<div id="nombre">Contenido</div>
```
Y enlazarlo:
```css
#nombre {
    background-color: rgb(0, 0, 255);
    color: red;
}
```
En Mediaqueries, se asegura que la página se vea equitativa en diferentes tamaños de pantalla, como en este ejemplo:
```css
@media only screen and (max-width: 600px) {
    body {
        background-color: lightblue;
    }
}
```
