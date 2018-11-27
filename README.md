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
El valor del atributo "Class" se puede utilizar cuando quieras
## 6. código para hacer un enlace a otra página y que esta se abra en una nueva ventana
```html
 <a href="pagina.html" target="_blank">Título del enlace</a>.
```
## 7. ¿Qué son las pseudoclases?, pon ejemplos.

