+ En un archivo de Python, escribe el siguiente código:

```python
from sense_hat import SenseHat

sense = SenseHat()

r = 255
g = 255
b = 255

sense.clear((r, g, b))
```

+ Graba y ejecuta tu código. La matriz LED se volverá blanca brillante.

+ Las variables `r`, `g`, y `b` representan los colores rojo, verde y azul. Sus valores especifican lo brillante que debe ser cada color; cada valor puede ser entre `0` y `255`. En el código anterior, se ha utilizado el valor máximo para cada color, por lo que el resultado es blanco.

+ También puedes definir los tres valores RGB de un color usando una sola línea de código:

```python
red = (255,0,0)
```
 <iframe src="https://trinket.io/embed/python/a588ddedcf" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>

+ Cambia el valor de uno de los colores, luego ejecuta el código nuevamente. ¿Qué ves?

+ ¿Qué otros colores puedes crear?
