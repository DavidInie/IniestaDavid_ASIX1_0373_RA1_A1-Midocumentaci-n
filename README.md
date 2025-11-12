# IniestaDavid_ASIX1_0373_RA1_A1-Midocumentaci-n
# APUNTES LENGUAJE DE MARCAS

## Etiquetas básicas de Markdown

- __Encabezados:__ Llevan un estilo asociado y casa uno sirve para iniciar sesion de documentos: Para hacer un encabazado en Markdown, utilizaremos la etiqueta (#).

# Esto es un encabezado H1
## Esto es un encabezado H2
### Esto es un encabezado H3
#### Esto es un encabezado H4
##### Esto es un encabezado H5
###### Esto es un encabezado H6


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

__##Para hacer parrafos le tendremos que dar 2 veces al intro.__

*Hola como estas:* Esto sera un parrafo.


*Bien y tu:* Se ha hecho un parrafo.


__Los acentos para la izquierda, sirven para ver la etiqueta, esto lo utilizaremos para poner una etiqueta HTML.__

```html
    <p>esto sera un parrafo</p>
```

__Para poner un link utilizaremos la etiqueta:__

[Pagina oficial de marca](https://www.marca.com/ "Texto adicional del enlace")   


 <!-- EXPLICAR MEJOR. -->
__Para poner una imagen utilizaremos la estiqueta:__ Aqui lo mas importante, es tener la imagen en una carpeta dentro del repositorio que hemos creado. Cuando hayamos hecho eso tendremos que poner la ruta.
![alt text](./images.jpg "Imagen astronauta")


__Para hacer una tabla__ Utilizaremos las barras(||), |-----------| Esto lo utilizaremos para darle el ancho a la tabla.

| Jugador | Equipo | Nombre |
|-----------:|:-----------:|:-----------|
| 10 | Barça | Messi |
| 8 | Barça |Pedri|
| 1 | Barça | Joan |// -->


# Como hacer un commit a github desde linea de comandos.
1. El primer paso, es entrar a github y coger el enlace de html.
![alt text](./img/caplink.png "Imagen astronauta")
2. Una vez copiado el enlace, iremos a la carpeta del repositorio y abriremos el cmd.
![alt text](./img/cap1commit.png "Imagen astronauta")
3. Una vez abierto el cms ejecutaremos el comando (git clone "enlace del repostioria HTML")
![alt text](./img/cap2commit.png "Imagen astronauta")
5. Cuando hayamos clonado el repositorio, tendremos que abir el cmd dentro de la carpeta del repositorio.
![alt text](./img/cap3commit.png"Imagen astronauta")
6. Una vez ejecutado el git clone, haremos estos pasos; 1.git init 2.git add . 3.git commit -m "nombre que queremos que tenga el commit" 4.git push origin main.
![alt text](./img/cap4commit.png "Imagen astronauta")





