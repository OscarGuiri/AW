## HTML y CSS
## 1. Estructura mínima de una web
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>

```
## 2.Explica las 3 formas de usar CSS en HTML
#### Hay de forma externo, la cual en la cabecera del HTML, el bloque <head> </head>, incluimos una relación al archivo CSS
#### Ej:
#### externo
```html
<link rel="stylesheet" type="text/css" href="index.css" />
```
#### Interno, la cual añadimos directamente en la cabecera HTML del documento.
```html
<!DOCTYPE html>
<html>
<head>
    <title>Título de la página</title>
    <style type="text/css">
        div {
            background:#FFFFFF;
        }
    </style>
</head>

```
#### embedido, la cual es poner el CSS directamente en una etiqueta
```html
p>¡Hola <span style="color:#FF0000">amigo lector</span>!</p>

```
## 3. Crea una lista sin ordenar con 5 ingredientes de una receta de cocina
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<h1>Como hacer cuscus</h1>
<ul>
	<li>1.Abre la lata de cuscus</li>
	<li>2.Ponlo en el plato</li>
	<li>3. Ya está, enorabuena</li>

</ul>

</body>
</html>
```
## 4. Como se puede incluir javascript en HTML
Con el elemento SPAN
### EJ: 
```html
<span onclick="alert('hola mundo!');">Clic aqu&iacute;</span>
```
## 5 ¿Que diferencia hay entre una clase y una ID
El valor del atributo “id” de un elemento es único; es decir, no debería haber otro elemento con el mismo nombre de identificador (id) dentro de tu documento HTML. 
El valor del atributo "Class" se puede utilizar cuando quieras.
## 6. código para hacer un enlace a otra página y que esta se abra en una nueva ventana
```html
 <a href="pagina.html" target="_blank">Título del enlace</a>.
```
## 7. ¿Qué son las pseudoclases?, pon ejemplos.
Una pseudoclase CSS es una palabra clave que se añade a los selectores y que especifica un estado especial del elemento seleccionado. 
### Ej:
```html
:hover
```
## 8. Explica el modelo de caja de CSS (margin, border y padding)
### margin: Limpia un área fuera de la frontera. El margen es transparente.
### border  Un borde que gira alrededor del relleno y el contenido
### padding Limpia un área alrededor del contenido. El relleno es transparente.
## 9. Explica que son los selectores de CSS y pon ejemplos
Son las formas para seleccionar los elementos para luego añadirle caracteristicas.
### Ej: 
#### Universal
```html
* {
  margin: 0;
  padding: 0;
}
```
#### De clase
```html
.destacado { color: red; }
```
## 10 Di a quien afectan:
### p a { color: red; - A - a ese parafo??
### p > a { color: red; } ??????
### h1 + h2 { color: red } - a esos dos heders 
### a[class] { color: blue; } - a todos los enclaces de todas las classes
### a[class="externo"] { color: blue; } - a la clase  "externo"
 ### a[href="http://www.ejemplo.com"] { color: blue; } - Solo ese enlace
 
