# **Menú Horizontal**

La tecnología es una herramienta muy importante para la comunicación entre personas, por eso la poblacion a nivel mundial utilizan las famosas **redes sociales**. Aquellas que nos permiten romper la barreras de la distancia. ¿Pero por qué hablamos de ello? y ¿Qué tiene que ver con el tema princiapal?
Pues hay una barra muy importante en cualquier red social, y son las barras de menú.
Nosotros veremos como podemos realizar una barra  dinámica, esto que permite una mejor navegacion por cualquier pagina, ya que podemos encontrar diversidad de informacion en ella.

## Objetivos
* Realizar con exactitud un menu horizontal.
* Manejar las distintas propiedades.
* Manejar las seudoclases.
* Colocar color .


***
## Modelo
Para poder realizar este trabajo se mostrara el modelo a replicar.

[Menú Horizontal](https://fotos.subefotos.com/9da8149c853131e7e7282a30c9dc37e6o.gif)

---
## Estructura del proyect
Esta conformada por una:
* Carpeta Menú horizontal
* Carpeta css
* Un archivo Index
* Un archivo estilo(css)

---

## Estructura de un archivo Index

```` html

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Menu Horizontal</title>
    <link rel="stylesheet" href="css/main.css">
  </head>
  <body>

   <h1>MENÚ HORIZONTAL</h1>
   <nav>
     <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Sobre mí</a></li>
      <li><a href="#">Portafolio</a></li>
      <li><a href="#">Contacto</a></li>
      <li><a href="#">Noticia</a></li>
    </ul>
    </nav>
  </body>
</html>

````

----
## Código del archivo de css
---
```` css
/*Colocamos un estilo de fuente al body*/
body {
  font-family: sans-serif;
}

nav {
  /*outline: 1px solid yellow;*/
}

 ul {
  /*outline: 1px solid yellow;*/
  margin: 0;
  padding: 0;
  background-color:rgba(15, 15, 14, 0.85); /* fondo plomo*/
  list-style: none;
  line-height: 3rem;
  /*overfloat: auto;*/
  /*devuelve su contexto de bloque a float */
}
li {
  width: 8rem;
  display: inline-block;
  text-align: center;
  /* float: left */
/*es otra propiedad que permite posicionar una al lado de otra  */

````
