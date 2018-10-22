Como pudiste observar, con definir las posiciones no alcanza, hay un grupo de propiedades que afectan a la posición, como el agrupamiento y el modelo de caja de los elementos. Por suerte, para que resulte menos azaroso contamos con métodos de posicionamiento que nos ayudan a definir mejor cómo serán las interacciones respecto a la posición.

Por defecto, el posicionamiento es `static`, y anula las propiedades de `top`,`right`,`bottom` y `left` y pone el elemento de acuerdo al flujo normal.
Los otros métodos son:

- `relative`, es el posicionamiento relativo al normal.
- `absolute`, es el posicionamiento relativo respecto del posicionamiento del elemento padre.
- `fixed`, es posicionamiento fijo en la pantalla, es decir, al desplazarse hacia abajo o arriba, el elemento con este posicionamiento seguirá presente en la pantalla.

> Veamos si se entiende. Escribí lo siguiente en el cuadro de la derecha:

> ```css
> .cuadrado {
  top: 0;
  right: 0;
  position: absolute;
}
>```
