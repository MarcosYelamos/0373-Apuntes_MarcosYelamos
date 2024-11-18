# ApuntesASIX1

## Primer capítulo: GITHUB Y PAGES
AL crear un repositorio en Github siempre hay que inicializarlo añadiendo el "READE.md".

"IMPORTANTE": Debemos estar en un cmd para ejecutar los comandos y tener en cuenta la ruta de donde estamos, preferiblemente en la ruta donde se va a meter el reposiorio o donde ya esta.

__Para clonar el repositorio de github y poder trabajarlo en local:__
```
"git clone" (ruta del repositorio a clonar).
```
Para añadir todo lo que hemos modificado habra que ejecutar estos 3 comandos:
```
git add.(Añadir las cosas nuevas)
git commit -m "(Nombre del commit)"
git push origin main (Subir del origen a la rama main de github)
```
Una vez ejecutados si fueramos al github veriamos que todo lo que hemos hecho en local se habría subido.

__Otros comandos de git:__
EL git init git branch (Para ver en que rama está el repositorio) git branch -M main (Le dice que la rama donde va a poner el rerpositorio es.main).

El git pull para traer de gtihub a mi ordenador.
<br>

#### PAGES
Para hacer que un repositorio de github se transforme en pagina web iremos a configuración (settings), en el menú de la izquierda seleccionaremos pages.
Seleccionamos la rama(Branch) Main y le damos a guardar (save). Al hacer esto y esperar un poco se nos creará un enlace a nuestra página.
<br>
<br>

## Segundo capítulo: Markdown 

(#) Esto sirve para poner encabezados, hay 6 niveles como en HTML, al poner este encabezado te pone un enlace en el título.
```
## Segundo nivel de encabezados
### Tercero nivel de encabezados
#### Cuarto nivel de encabezados
##### Quinto nivel de encabezados
###### Sexto nivel de encabezados
```

Este texto esta en *cursiva*- * *

Este texto esta en _cursiva_. _ _

Este texto esta en __negrita__. __ __

Este texto esta en **negrita**. ** **

Este texto esta en **_negrita y cursiva_**. ** _ _ ** 

Este texto esta en __*negrita y cursiva*__. __ * * __

1. Primera opción de menu. Esto es una lista ordenada.
2. Segunda opción de menu.
3. Tercera opción de menu.

(La lista desordenada se hace con el - , con * y con el +)
* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primera submenú 
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada
<br>
Hay que dejar un espacio en blanco para que siga en otra linea 
<br>

**Como mostrar código en un repositorio**

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```
<br>

### Como poner un link
[Pagina web de Jesuites Bellvitge](https://www.fje.edu/ca/fje "Titulo opcional")

### Como poner una imagen
![Esto es una foto](https://inhispania.com/wp-content/uploads/2021/05/1.jpg "Esto es un foton de si")

Una tabla:

|Titulo 1| Titulo 2| Titulo 3 |
|---------------|:------------:|---------:|
|SMX2 |Curso 2324|25|
|**ASIX1**|Curso 2425|33|
|DAW2|Curso 2425|32|
<br>

## Tercer capítulo: HTML 

```
Etiquetas de apertura y cierre.
apertura --> <p>(contenido visible)</p> <-- cierre

Todo el parrafo incluyendo las etiquetas se llama elemento
<p class "valor"> texto a mosrar </p>

Anidar etiquetas: Meter una etiqueta dentro de otra
<p> balala <strong> negrita </strong> adadada <p>

El texto que esta en strong estara en negrita y lo demas no, todo en conjunto sera un parrrafo.

Las etiquetas no tienen porque tener que ir solas, en la etiqueta de apertura se ponen los atributos, siempre van separados con un espacio.
Algunas etiquetas como img necesitan si o si atributos.

<img href="./imagen">
Para añadir una imagen

<br> --> para dejar un espacio en blanco entre lineas.
```

HTML tiene una estructura. Siempre empieza con el doctype html para indicarle al navegador web que tipo de lenguaje es y así lo pueda renderizar.

html:5 para añadir al archivo las partes de un documento html.

```
<!DOCTYPE html> (Le decimos al docuemnto que tipo de documento es)

<html lang="en"> Inicio, se vaa poner el codigo a partir de aqui.

</html> Es el cierre de la etiqueta anterior. Despues de esta etiuqeta no se pone codigo.

encabezado --> <head> </head> (Va al principio de la pagina es la parte donde definimos las caracetristicas de la pagina y donde metemos todo el contenido no visible por los visitantes. Enlaces)


<meta charset="UTF-8"> que set de caracteres tiene que cojer la pagina, en este caso coje el que utilizamos, con la ñ añadida por ejemplo.

<meta name="viewport" content="width=device-width, initial-scale=1.0"> Como se ve a ver el ancho de la pantalla.

<title>Document</title> Es el titulo de la pagina. en la pestaña del navegador se vera lo quese ponga

<link rel="stylesheet" href="style.css">: vincular la página con la pagina de estilos.

<favicon> para definir el icono de la pagina web que  s eve arriba en la pestaña del navegador.

cuerpo --> <body> </body>
```

Elemento body:
Aquí va lo que se verá en la página web, aquí va todo el contenido y se hace mediante etiquetas.

Hay dos categorias de etiquetas:

Etiquetas de bloque: Cuando se acaba de renderizar el contenido de etiqueta deja un espacio de linea. Ej: las etiquetas de titulo, parrafo, listas, tablas.

Etiquetas de linea: Cuando se acaba de renderizar la etiqueta __NO__ hace un salto de linea. Ej: span , strong...

Algunos elementos de linea y bloque:

![Esto es una foto de ejemplos](./img/comparacion.png "Esto es una tabla con varios elementos de linea y bloque")

A la hora de hacer código HTML queremos que haya un orden para que sea legible así que habrá que tabular el código.

No todas la setiquetas se cierran o se abren.
<br>

#### Organización de los archivos
