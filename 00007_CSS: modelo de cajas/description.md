Todos los elementos de HTML pueden ser considerados cajas, incluso aunque no te lo parezca.

Esto nos sirve para diseñar nuestro _layout_. A partir de definir una serie de propiedades en nuestras reglas de CSS, nos es posible cambiar aspectos sobre los tamaños de los elementos y cómo se relacionan con otros. 

<img src="https://raw.githubusercontent.com/smartedu-mumuki/mumuki-guia-html-diseno/master/images/Screen%20Shot%202018-04-16%20at%2012_1523891043949.03.06.png" alt="Screen Shot 2018-04-16 at 12_1523891043949.03.06.png" width="100%" height="auto">

Cada una de estas cajas se compone de 4 secciones: _margin_, _border_, _padding_ y el contenido. :hushed:

Además de manipular estas propiedades de la caja de un elemento, también se combina con las propiedades que ya vimos, como el `height` y el `width`. Por lo tanto, al momento de calcular que tan alto o ancho es un elemento, debemos considerar su caja más el alto y ancho establecido en `height` y `width`.


> Si un elemento tiene establecido 320px de ancho, y la caja la configuramos de tal manera que agrega 30px de márgenes. ¿Cuánto será el ancho final del elemento?

