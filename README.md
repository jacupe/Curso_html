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



   # 📘 Organización de texto en HTML

HTML permite estructurar y organizar el contenido de una página web mediante etiquetas.  
Estas etiquetas ayudan a que la información sea más clara, ordenada y fácil de entender.

---

# 🏷️ Encabezados en HTML

Los encabezados se utilizan para colocar títulos y subtítulos según el nivel de importancia.

| Etiqueta | Función |
|-----------|-----------|
| `<h1>` | Título principal |
| `<h2>` | Subtítulo |
| `<h3>` | Tema secundario |
| `<h4>` | Subtema |
| `<h5>` | Encabezado pequeño |
| `<h6>` | Encabezado de menor tamaño |

## ✨ Ejemplo

```html
<h1>Mi primera página</h1>
<h2>Sección principal</h2>
<h3>Información adicional</h3>
```

---

# 📝 Párrafos y énfasis

Los párrafos sirven para escribir textos o descripciones dentro de la página web.

Las etiquetas de énfasis permiten resaltar palabras importantes.

| Etiqueta | Función |
|-----------|-----------|
| `<p>` | Crear párrafos |
| `<strong>` | Mostrar texto importante en negrita |
| `<em>` | Mostrar texto con énfasis en cursiva |

## ✨ Ejemplo

```html
<p>HTML permite crear páginas web.</p>

<p>
Este texto tiene una palabra
<strong>importante</strong>
y otra palabra con
<em>énfasis</em>.
</p>
```

---

# 📋 Listas en HTML

Las listas ayudan a organizar información de forma ordenada o con viñetas.

| Etiqueta | Función |
|-----------|-----------|
| `<ul>` | Lista desordenada |
| `<ol>` | Lista ordenada |
| `<li>` | Elemento de lista |

## ✨ Ejemplo

```html
<ul>
    <li>Computadora</li>
    <li>Teclado</li>
</ul>

<ol>
    <li>Encender PC</li>
    <li>Abrir navegador</li>
</ol>
```

---

# 💬 Citas y referencias

Estas etiquetas se utilizan para mostrar frases importantes o nombres de autores.

| Etiqueta | Función |
|-----------|-----------|
| `<blockquote>` | Crear una cita larga |
| `<cite>` | Mostrar autor o referencia |

## ✨ Ejemplo

```html
<blockquote>
"La educación es la clave del éxito."
</blockquote>

<cite>Autor desconocido</cite>
```

---

# 💻 Código y texto técnico

Estas etiquetas sirven para mostrar código de programación manteniendo su formato.

| Etiqueta | Función |
|-----------|-----------|
| `<code>` | Mostrar código |
| `<pre>` | Mantener espacios y saltos de línea |

## ✨ Ejemplo

```html
<pre>
<code>
<h1>Hola Mundo</h1>
</code>
</pre>
```

---

# 📏 Líneas y saltos de línea

Se utilizan para separar contenido o realizar saltos de línea.

| Etiqueta | Función |
|-----------|-----------|
| `<hr>` | Crear línea horizontal |
| `<br>` | Realizar salto de línea |

## ✨ Ejemplo

```html
<p>Bienvenidos</p>

<hr>

<p>
Curso básico<br>
de HTML
</p>
```