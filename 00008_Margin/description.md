Margin es el área por fuera del borde de la caja de un elemento. Es de color transparente.

Si recordamos la imagen del ejercicio anterior, podemos ver que el _margin_ rodea al borde en todas las direcciones, es decir que deberemos definir el margin para la derecha, izquierda, arriba y abajo.
Por ejemplo:

```css
.con_margen {
  margin-top: 10px; /*arriba*/
  margin-right: 5px;  /*derecha*/
  margin-bottom: 5px; /*abajo*/
  margin-left: 0px; /*izquierda*/
}
``` 
También es posible hacer lo mismo con una sola línea:

`margin: 10px 5px 5px 0px;`

Y esto se asigna en el orden del sentido horario (arriba-derecha-abajo-izquierda).

> A ver si se entiende, agrega margen a izquierda y la derecha de 5px al elemento `p`.