# IniestaDavid_ASIX1_0373_RA1_A1-Midocumentaci-n
# APUNTES LENGUAJE DE MARCAS


# GitHub:


## Como crear un repositorio en github:
1. El primer paso, sera ir a la pestaña de repositorios y darle a new.
![alt text](./img/crearrepo/cap1.png "Imagen 1")
2. El segundo paso, es poner el nombre, descripción y coger la opción de repo publico y pibrado.
![alt text](./img/crearrepo/cap2.png  "Imagen 2")
3. Una vez hecho eso los pasos, tendremos que marcar la opción de Add README.
![alt text](./img/crearrepo/cap3.png  "Imagen 3")
4. Una vez marcada la opción, le daremos a crear reposositorio y ya tendremos creado el repositorio.
![alt text](./img/crearrepo/cap3.png  "Imagen 4")


## Como hacer un commit a github desde linea de comandos.
1. El primer paso, es entrar a github y coger el enlace de html.
![alt text](./img/crearcommit/caplink.png "Imagen abir cmd")
2. Una vez copiado el enlace, iremos a la carpeta del repositorio y abriremos el cmd.
![alt text](./img/crearcommit/cap1commit.png "Imagen enlace")
3. Una vez abierto el cmd ejecutaremos el comando (git clone "enlace del repostioria HTML")
![alt text](./img/crearcommit/cap2commit.png "Imagen cmd")
4. Cuando hayamos clonado el repositorio, tendremos que abir el cmd dentro de la carpeta del repositorio.
![alt text](./img/crearcommit/cap3commit.png "Imagen abir cmd")
5. Una vez ejecutado el git clone, haremos estos pasos; 1.git init 2.git add . 3.git commit -m "nombre que queremos que tenga el commit" 4.git push origin main.
![alt text](./img/crearcommit/cap4commit.png "Imagen cmd")


## Como hacer github pages:
1. El primer paso, es ir a la pestaña de repositorios, y entrar al repositorio.
![alt text](./img/pages/cap1.png "Imagen abir cmd")
2. Una vez dentro del repositorio, iremos a settings.
![alt text](./img/pages/cap2.png "Imagen enlace")
3. Cuando estemos dentro de settings, iremos a la parte izquierda y entraremos a PAGES.
![alt text](./img/pages/cap3.png "Imagen cmd")
4. Cuando entremos, veremos que pone none.
![alt text](./img/pages/cap4.png "Imagen abir cmd")
5. En la parte que pone none, tendremos que darle encima y poner save y darle a save.
![alt text](./img/pages/cap5.png "Imagen abir cmd")
6. Una vez cambiada la ruta, esperaremos unos minutos y ya tendremos hecho el pages.
![alt text](./img/pages/cap6.png "Imagen abir cmd")


# Etiquetas básicas de Markdown


## Encabezados Markdown
- __Encabezados:__ Llevan un estilo asociado y cada uno sirve para iniciar el documento: Para hacer un encabazado en Markdown, utilizaremos la etiqueta (#).


# Esto es un encabezado H1
## Esto es un encabezado H2
### Esto es un encabezado H3
#### Esto es un encabezado H4
##### Esto es un encabezado H5
###### Esto es un encabezado H6


## Estilos Markdown
- En Markdown para poner estilos de letra utilizaremos:
    - Esto esta  __en negrtia__
    - Esto esta **en negrita**
    - Esto esta en _curiva_
    - Esto esta en *cursiva* 
- Para juntar los dos estilos utilizaremos los dos comandos, los combinaremos:
    - Esto esta en __*cursiva y negrita*__


<!-- __*ABRIR ETIQUETA 1*__
    ABRIR ETIQUETA 2
        contenido 
    CERRAR ETIQUETA 2
CERRAR ETIQUETA 1 -->
## Listas Markdown
- Para hacer una lista ordenada utilizaremos, (1. 2. 3.)
Lista ordenada:
1. Elemento 1
2. Elemento 2
3. Elemnto 3


Lista desordenada: Para hacer lista desordenada utilizaremos (*) pero tambien podemos utilizar __+__ y __-__ para hacer una lista desorndenada.
* Elemento desordenado 1
* Elemento desordenado 2
* Elemento desordenado 3


Tambien podemos hacer un anexado para hacer una lista ordenada y una desordenada.
1. Elemento 1
    * Elemento desordenado 1.1
    * Elemento desordenado 1.2
2. Elemento 2
    * Elemento desordenado 2.1
    * Elemento desordenado 2.2
2. Elemento 3


## Parrafos Markdown
__##Para hacer parrafos le tendremos que dar 2 veces al intro.__

*Hola como estas:* Esto sera un parrafo.


*Bien y tu:* Se ha hecho un parrafo.


## Incluir HTML Markdown
__Los acentos para la izquierda, sirven para ver la etiqueta, esto lo utilizaremos para poner una etiqueta HTML.__

```html
    <p>esto sera un parrafo</p>
```

## Enlace Markdown
__Para poner un link utilizaremos la etiqueta:__
([Pagina oficial de marca](https://www.marca.com/ "Texto adicional del enlace")) 


[Pagina oficial de marca](https://www.marca.com/ "Texto adicional del enlace")   


## Imagen Markdown
 <!-- EXPLICAR MEJOR. -->
__Para poner una imagen utilizaremos la estiqueta:__ Aqui lo mas importante, es tener la imagen en una carpeta dentro del repositorio que hemos creado. Cuando hayamos hecho eso tendremos que poner la ruta.
![alt text](./img/images.jpg "Imagen astronauta")



## Tabla Markdown
__Para hacer una tabla__ Utilizaremos las barras(||), |-----------| Esto lo utilizaremos para darle el ancho a la tabla.

| Jugador | Equipo | Nombre |
|-----------:|:-----------:|:-----------|
| 10 | Barça | Messi |
| 8 | Barça |Pedri|
| 1 | Barça | Joan |// -->


# Etiquetas básicas de HTML


- En HTML las etiquetas tienes que abrirse u cerrarse. Abrir etiqueta (<>), para cerrar una etiqueta utilizarems (/), (</>)


## Estructura basica HTML

- La estructura basica de HTML se empieza abriendo una etiqueta (<!DOCTYPE html>) cuando hayamos abirto la etiqueta, abriremos otra en la que tendremos que poner el lenguaje que queremos que tenga la pagina. (<html lang="en">), despues de eso tendremos que abir y cerrar la etiqueta de (<head></head>). Sirve para añadir información extra, aqui dentro tendremos que poner los enlaces a otra pagina como a CSS o tambien podemos poner el favicon.


```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Prueba</title>
        <link rel="stylesheet" href="style.css">
    </head>
```


## Normas básicas de HTML:


- Las etiquetas HTML suelen venir en pares, con apertura y cierre (por ejemplo, <p></p>).


- Algunas son etiquetas vacías, es decir, no tienen etiqueta de cierre, como (<img>, <br> o <input>).


- Las etiquetas deben anidarse correctamente: si una etiqueta se abre dentro de otra, debe cerrarse antes de que se cierre la anterior.


- Los atributos se colocan en la etiqueta de apertura y tienen el formato nombre="valor".


- Recomendación: aunque HTML no distingue entre mayúsculas y minúsculas, se aconseja escribir todo en minúsculas.


## Legibilidad y organización del código


La legibilidad del código es la claridad con la que está escrito, para que cualquier persona pueda entenderlo fácilmente.  
**Es fundamental que el código HTML sea legible.**


Normalmente no trabajaremos solos, por lo que el código debe ser comprensible también para otros.  
Incluso si solo lo modificamos nosotros, la legibilidad ayuda a recordar lo que hemos hecho.


**La organización del código fuente** implica estructurar la aplicación en varios archivos y clasificarlos en los directorios necesarios.


**Técnicas para mejorar la legibilidad y organización:**
- Uso de comentarios.
- Indentación del código.
- Buena organización de los archivos.


## Encabezados HTML
- __Encabezados:__ Llevan una estiqueta asociada y casa uno sirve para iniciar el documento: Para hacer un encabazado en HTML, utilizaremos la etiqueta (h1, h2, h3, h4, h5, h6).


```html
    <h1>Esto  en un encabezado H1</h1>
    <h2>Esto  en un encabezado H2</h2>
    <h3>Esto  en un encabezado H3</h3>
    <h4>Esto  en un encabezado H4</h4>
    <h5>Esto  en un encabezado H5</h5>
    <h6>Esto  en un encabezado H6</h6>
```
# Esto  en un encabezado H1
## Esto  en un encabezado H2
### Esto  en un encabezado H3
#### Esto  en un encabezado H4
##### Esto  en un encabezado H5
###### Esto  en un encabezado H6


## Estilos HTML

```html
    <strong>Se utiliza (strong) para poner negregita el texto</strong>
    <br>
    <em>Se utiliza (em) para poner curvisa el texto </em>
    <br>
    <p>Tambien podemos juntar los dos estilos</p>
    <br>
    <strong><em>Juntaremos las dos etiquetas para hacer un combinado de estilos</em></strong>
```



