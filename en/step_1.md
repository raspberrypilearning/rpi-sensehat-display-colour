- In a Python file, type in the following code:

    ```python
    from sense_hat import SenseHat

    sense = SenseHat()

    r = 255
    g = 255
    b = 255

    sense.clear((r, g, b))
    ```

- Save and run your code. The LED matrix will then go bright white.

<iframe src="https://trinket.io/embed/python/a588ddedcf" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

- The variables `r`, `g` and `b` represent the colours red, green, and blue. The numbers they contain specify how bright each colour should be; the value can be between 0 and 255. In the above code the maximum value for each colour has been used, so the result is white.

- Change the values to specify 255 red but 0 green and blue, then run the code again.

- What other colours can you make?
