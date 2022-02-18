# Proyecto VIAJAJA :airplane:

Es una página web estática (por ahora) en el que simula ser una agencia de viajes virtual donde podrás navegar entre las diferentes secciones y está desarrollada con:

- HTML
- CSS
- SASS
- BootStrap

### HTML
HTML es un lenguaje de marcado de etiquetas que se utiliza para el desarrollo de páginas de Internet. Se trata de la siglas que corresponden a HyperText Markup Language, es decir, Lenguaje de Marcas de Hipertexto.

[HTML](https://www.w3schools.com/html/) ***sitio no oficial***.

### CSS
CSS son las siglas en inglés para "hojas de estilo en cascada", en inglés, Cascading Style Sheets. Básicamente, es un lenguaje que maneja el diseño y presentación de las páginas web, es decir, cómo lucen cuando un usuario las visita. Funciona junto con el lenguaje HTML que se encarga del contenido básico de las páginas.

[CSS](https://www.w3schools.com/css/) ***sitio no oficial***.

### SASS
Sass es un preprocesador de CSS que permite generar de manera automática hojas de estilo, añadiéndoles características que no tiene CSS y que son propias de los lenguajes de programación, como pueden ser variables, funciones, selectores anidados, herencia, entre otros.

[SASS](https://sass-lang.com/)

### Instalación
Se requiere Node.js v14.15+ para comenzar con el procedimiento.

Instalar dependencias:

```sh
$ npm init 
$ npm install -D node-sass nodemon
```
Modificar los scripts en el archivo ***package.json*** para comenzar a compilar:

```sh
 "build-css": "node-sass --include-path scss scss/style.scss css/style.css",
 "watch.css": "nodemon -e scss -x \ "npm run build-css""
```

Ejecutar el script en la terminal:

```sh
$ npm run watch-css
```

### Bootstrap
Bootstrap es una biblioteca multiplataforma o conjunto de herramientas de código abierto para diseño de sitios y aplicaciones web. Se decidió utilizarla en el proyecto ya que ayudaría a obtener un diseño Responsive y moderno sin demasiadas complicaciones.

[Bootstrap](https://getbootstrap.com/)

Para poder aplicar Bootstrap se puede hacer de dos formas:

1. Linkeando la CDN de CSS y JavaScript:

```sh
"<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">"

"<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>"
```
2. Descargando los archivos CSS y JavaScript y linkeandolos al html:

```sh
"<link rel="stylesheet" href="./css/bootstrap-5.1.3-dist/css/bootstrap.css">"

"<script src="./js/bootsrap.js"></script>"
```

### Desarrollo

Desarrollado por [Howard Parra](https://github.com/hparra07) para el curso de Desarrollo Web en [Coderhouse](https://www.coderhouse.com/).

Puedes visitar VIAJAJA en este [link](https://hparra07.github.io/miProyecto/).
