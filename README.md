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


## Tercer capítulo: HTML 

