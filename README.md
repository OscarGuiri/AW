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
