=================
OKFN WordPress Theme
=================

OKFNWP es un tema WordPress que corre en el sitio web de [okfn.es](http://okfn.es) construido sobre *Bootstrap* y *Less*.

Primeros pasos
---------------
**Hay que tener instalado:**
  * [Node.js](http://nodejs.org): se utiliza el instalador del sitio web de NodeJS.
  * [Grunt](http://gruntjs.com/): se lanza con `[sudo] npm install -g grunt-cli`
  * [Bower](http://bower.io): se lanza con `[sudo] npm install -g bower`

Para comenzar, se lanza esta línea:

`npm install && bower install && grunt watch`


Plantillas
---------

**Página de inicio**

La plantilla de la página de inicio es una página de contenido de ancho completo. Se utiliza el atajo `[latestposts]` para mostras las últimas entradas publicadas.


Atajos
----------

**Últimas entradas**

Para añadir una fila de tres-columnas de las últimas entradas del blog, se utiliza:

  `[latestposts]`

Para cambiar el encabezamiento predeterminado que dice 'Latest posts from the blog', se escribe el atributo title en el parámetro `[latestposts]`:

`[latestposts title="Mi encabezamiento"]`
