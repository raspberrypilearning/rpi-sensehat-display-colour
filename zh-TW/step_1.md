+ In a Python file, type in the following code:

```python
from sense_hat import SenseHat

sense = SenseHat()

r = 255
g = 255
b = 255

sense.clear((r, g, b))
```

+ Save and run your code. The LED matrix will then go bright white.

+ The variables `r`, `g`, and `b` represent the colours red, green, and blue. Their values specify how bright each colour should be; each value can be between `0` and `255`. In the above code, the maximum value for each colour has been used, so the result is white.

+ You can also define all three RGB values of a colour using a single line of code:

```python
red = (255,0,0)
```
 <iframe src="https://trinket.io/embed/python/a588ddedcf" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>

+ Change the value of one of the colours, then run the code again. What do you see?

+ Which other colours can you make?
