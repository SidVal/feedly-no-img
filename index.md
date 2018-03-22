---
layout: base
title: Feedly No Img Web
---

## How to use it

1. Drag the link into your Bookmarks Bar
1. Go to Feedly.com and log-in
1. Check your favorite blog with some content (shows images by default)
1. Clic your bookmark's link created in point 1.
1. Whalla! :tada: Images gone! 

>Ps: if you want to reset the images, just press "F5" to refresh the site. Now the images shows up again.

### Drag This to Bookmarks Bar
<div class="box">
  <strong><a href="javascript:(function()%7B(function(i%2Cn%2Cj%2Ce%2Cc%2Ct%2Ccss)%7B%20css%3Di.createElement(n)%3Bt%3Di.getElementsByTagName(c)%5B0%5D%3Bcss.href%3Dj%3Bcss.rel%3De%3B%20t.insertAdjacentElement('beforeend'%2Ccss)%3B%7D)%20(document%2C'link'%2C'https%3A%2F%2Fcdn.rawgit.com%2FSidVal%2Ffeedly-no-img%2Fmaster%2Fassets%2Ffeedly-no-img.css'%2C'stylesheet'%2C'head')%3B(function()%20%7Bvar%20link%20%3D%20document.querySelector(%22link%5Brel*%3D'icon'%5D%22)%20%7C%7C%20document.createElement('link')%3Blink.type%20%3D%20'image%2Fx-icon'%3Blink.rel%20%3D%20'shortcut%20icon'%3Blink.href%20%3D%20'https%3A%2F%2Fraw.githubusercontent.com%2FSidVal%2Ffeedly-no-img%2Fmaster%2Fassets%2Ffeedly-no-img.png'%3Bdocument.getElementsByTagName('head')%5B0%5D.appendChild(link)%3B%7D)()%3Balert(%22Feedly%20'No%20Img'%20ON%20-%20Press%20F5%20if%20you%20want%20to%20turn%20off.%22)%3Bconsole.clear()%7D)()">Feedly No Img</a></strong>
  </div>

### Check this Tutorial | Feedly No Img Demo
You can see right now a demo: [https://sidval.github.io/feedly-no-img/tutorial](https://sidval.github.io/feedly-no-img/tutorial)

<br />

***

<br />

## Feedly No Img (The Idea)

When we read the news in Feedly, many times we only want "only text" WITHOUT images. 

I've tried many extensions in Chrome. 
But they tired me, besides that (like it or not), they bring performance problems in the chrome program. 
Many extensions do more than hide images, some put advertisements, pop-ups, and so on. Another that "worked", also hide buttons, and images that are necessary for reading Feedly, so they do not serve the purposes I was looking for. 

So here I have the solution for this situation.

<br />

***

<br />


## Spanish Version 

### Feedly No Img :es: 

Cuando leemos las noticias en Feedly, muchas veces queremos solo texto.

He probado muchas extensiones en Chrome.
Pero me cansaron, además de que (nos guste o no), traen problemas de rendimiento en el programa.
Muchas extensiones hacen algo más que ocultar imagenes, algunas ponen publicidad, pop-ups, etcétera.
Otra que "funcionaba", también me ocultaba botones, e imágenes que sí son necesarios para la lectura de Feedly., así que no sirven para los fines que buscaba.

Así que aquí tengo la solución para Chrome

### Cómo funciona

1. Con el ratón haz clic sobre el enlace que verás a continuación y sin soltar el clic lo arrastras hasta tu lista de favoritos del navegador web Chrome.
1. Abre una pestaña nueva para <strong>Feedly.com</strong> e ingresa a tu cuenta (debes estar registrado).
1. Ve a un sitio web, o cualquier colección de feeds que tengas, para leer contenido (que tendrá imagenes).
1. Haz clic en el enlace del favorito que tienes en tu lista de favoritos (el nuevo favorito que creaste en el punto 1).
1. Whalla! :tada: Lo hicimos! Las imágenes desaparecieron! 

>Pd: si quieres que las imágenes en Feedly vuelvan a aparecer, solo debes presionar la tecla "F5" para que Chrome refresque la página, y las imágenes vuelven a ser visibles.

## Arrastra este enlace a tus favoritos
<div class="box">
  <strong><a href="javascript:(function()%7B(function(i%2Cn%2Cj%2Ce%2Cc%2Ct%2Ccss)%7B%20css%3Di.createElement(n)%3Bt%3Di.getElementsByTagName(c)%5B0%5D%3Bcss.href%3Dj%3Bcss.rel%3De%3B%20t.insertAdjacentElement('beforeend'%2Ccss)%3B%7D)%20(document%2C'link'%2C'https%3A%2F%2Fcdn.rawgit.com%2FSidVal%2Ffeedly-no-img%2Fmaster%2Fassets%2Ffeedly-no-img.css'%2C'stylesheet'%2C'head')%3B(function()%20%7Bvar%20link%20%3D%20document.querySelector(%22link%5Brel*%3D'icon'%5D%22)%20%7C%7C%20document.createElement('link')%3Blink.type%20%3D%20'image%2Fx-icon'%3Blink.rel%20%3D%20'shortcut%20icon'%3Blink.href%20%3D%20'https%3A%2F%2Fraw.githubusercontent.com%2FSidVal%2Ffeedly-no-img%2Fmaster%2Fassets%2Ffeedly-no-img.png'%3Bdocument.getElementsByTagName('head')%5B0%5D.appendChild(link)%3B%7D)()%3Balert(%22Feedly%20'No%20Img'%20ON%20-%20Press%20F5%20if%20you%20want%20to%20turn%20off.%22)%3Bconsole.clear()%7D)()">Feedly No Img</a></strong>
  </div>

### Ver demostración
Puedes mirar paso a paso cómo se hace aquí: [https://sidval.github.io/feedly-no-img/tutorial](https://sidval.github.io/feedly-no-img/tutorial)


***

## Transparencia, Seguridad & Privacidad

Si hay algo que me molesta cuando uso extensiones en Chrome, es que el desarrollador no explica cómo funcionan, o qué hacen realmente. Su código -por así decirlo, es privado.

En éste caso el código es abierto, y público.

Te explicaré qué hace, por qué y para qué. 
Si algo no te gusta, puedes decirlo, así creamos una versión nueva con tus cambios.

### Componentes

+ CSS (hojas de estilo)
+ 1 imagen (el favicon de la página)
+ Javascript (para las acciones)

Explicaré cada uno...

#### feedly-no-img.css
Es un archivo .CSS conocido como Hojas de Estilo cuya única misión es ocultar las imágenes visibles. Para ello usa la propiedad [`display:none;`](https://www.w3schools.com/css/css_display_visibility.asp). 

Puedes ver el [contenido del archivo aquí](https://github.com/SidVal/feedly-no-img/blob/master/assets/feedly-no-img.css).

Si no conoces nada sobre CSS, y deseas aprender más, lee: https://developer.mozilla.org/es/docs/Web/CSS

#### feedly-no-img.png
La única misión de ésta imagen es poner un favicon distinto cuando feedly tiene las imágenes ocultas, así puedes saber rápidamente cuando las imágenes se están escondiendo, o no.

Pestaña de Feedly por defecto, se verá con ésta imágen:

![Pestaña Feedly](https://s3.feedly.com/img/follows/feedly-follow-logo-green_2x.png)

Cuando has activado "Feedly No Img":

![Feedly-No-Img](https://raw.githubusercontent.com/SidVal/feedly-no-img/master/assets/feedly-no-img.png)

#### Javascript
No me considero para nada un programador Javascript.
Seguramente habrá mejores formas de lograr lo que he hecho, así que el código está abierto a futuras modificaciones.

El código Javascript del botón que hemos agregado a favoritos para ocultar las imágenes de Feedly está compuesto por cuatro partes:

* Inserta el [`feedly-no-img.css`](#feedly-no-img.css) en el `head` de *Feedly.com*
* Cambiar el favicon (la imagen de la pestaña) de *Feedly.com* por [`feedly-no-img.png`](#feedly-no-img.png)  para indicar al usuario que se ha activado "feedly-no-img".
* Envía un mensaje de alerta para que el usuario esté al tanto de que todo ha funcionado bien, y le recuerda que presionando "F5" se desactiva "Feedly-no-img".
* Limpia la consola del navegador (es un detalle técnico, para el usuario final no cambia nada).

##### Injectar css en head
Para ésta misión encontré el [código de *stereobird*](https://stackoverflow.com/a/35190227) y lo adapté a mis necesidades, para que busque el `.css` correspondiente.

El código quedó así:

```javascript
(function(i,n,j,e,c,t,css){ css=i.createElement(n);t=i.getElementsByTagName(c)[0];css.href=j;css.rel=e; t.insertAdjacentElement('beforeend',css);}) (document,'link','https://cdn.rawgit.com/SidVal/feedly-no-img/master/assets/feedly-no-img.css','stylesheet','head');
```

#### Cambiar Favicon de Página Web
Para ésta misión encontré el [código de *keparo*](https://stackoverflow.com/a/260876) y lo adapté para colocar la imágen de Feedly oscura. 

El código quedó así:

```javascript
(function() {
    var link = document.querySelector("link[rel*='icon']") || document.createElement('link');
    link.type = 'image/x-icon';
    link.rel = 'shortcut icon';
    link.href = 'https://raw.githubusercontent.com/SidVal/feedly-no-img/master/assets/feedly-no-img.png';
    document.getElementsByTagName('head')[0].appendChild(link);
})();
```

#### Mensaje
Es simple, solo avisa que está OK, y recuerda cómo volver los cambios hacia atrás.

```javascript
alert("Feedly 'No Img' ON - Press F5 if you want to turn off.");
```

#### Clear Console
Por una cuestión meramente técnica, me gusta como queda la consola del desarrollador limpia, así que agregué en el código Javascript una línea para limpiar la consola. 

`console.clear();`

### Bookmarklet
Una vez que todo el código estuvo listo, probado y lustrado, usé la página de Peter Coles: "[Bookmarklet Creator](https://mrcoles.com/bookmarklet/)" para llegar al resultado final, y obtener el enlace para que cualquier pueda tener esto en su navegador de Chrome.

<br />

***

### Dime qué piensas

* [¡Publica tu opinión aquí!](https://github.com/SidVal/feedly-no-img/issues/new?labels=comments&milestone=1&assignee=SidVal)
* Mira la lista de [**cosas por hacer**](https://github.com/SidVal/feedly-no-img/issues), puedes comentar y colaborar cuando quieras.

