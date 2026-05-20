# HTML
Lenguaje de marcado de texto, es la parte 
que nos permite estructurar nuestra pagina 
web,asi como el esqueleto de nuestra 
aplicacion.
Su principal objetivo es darle formato 
semantico a nuestra informacion a travez
del uso de ´elementos´ que asta a su vez 
esta conformaco por ´etiquetas´ de
apertura y cierre y ´contenido´
> [!TIP] En algunos casos encontraremos los ´elementos´
huerfano estos solo estan conformados por una sola ´etiqueta´

## Estructura de un elemento en html
![alt text] (image.png.)

## Estructura fundamental del documento html 
- ´<!DOCTYPE html>´ - Declaramos el tipo de 
- documento, este elemento huerfano indica el navegador que el documento con con el que se esta trabajando y que debera renderizar es ´html´, **Siempre debe estar en la primera linea**.
- ´<head></head>´ - Elemento de configuracion, contiene informacion importante sobre el documento como (titulo, enlaces, css, informacion para motores de busqueda, descripcion entre otrpos.)
-´<title></title>´ - Elemento de titulo de pagina, es el hijo de ´head´ y define el titulo que aparecera en la pestaña del navegador 
-´<body></body>´ - 
## Estructura de contenido semantico (seciones principales)


# Estructura de Contenido Semántico

Las etiquetas semánticas en HTML permiten organizar 
y estructurar mejor una página web. Su principal 
objetivo es darle significado al contenido para que 
sea más fácil de entender tanto para los usuarios 
como para los navegadores.

## Etiquetas semánticas principales

- `<header></header>` - Representa el encabezado de 
la página web. Generalmente contiene el título, logo 
o menú principal.

- `<nav></nav>` - Elemento de navegación. Se utiliza 
para colocar enlaces o menús de la página.

- `<main></main>` - Representa el contenido principal 
del documento. Aquí se coloca la información más 
importante.

- `<section></section>` - Sirve para dividir el 
contenido en diferentes secciones o temas relacionados.

- `<article></article>` - Representa contenido 
independiente como noticias, publicaciones o artículos.

- `<aside></aside>` - Contiene información adicional 
como anuncios, enlaces relacionados o contenido extra.

- `<footer></footer>` - Representa el pie de página. 
Generalmente contiene información de contacto, derechos 
de autor o redes sociales.

> [!TIP]
> El uso de etiquetas semánticas ayuda a mejorar la 
> organización del código, la accesibilidad y el 
> posicionamiento en buscadores como Google.

## Ejemplo básico

```html
<header>
   <h1>Mi Página Web</h1>
</header>

<nav>
   <a href="#">Inicio</a>
   <a href="#">Contacto</a>
</nav>

<main>
   <section>
      <article>
         <h2>Mi Artículo</h2>
         <p>Contenido del artículo.</p>
      </article>
   </section>
</main>

<footer>
   <p>Todos los derechos reservados</p>
</footer>
```