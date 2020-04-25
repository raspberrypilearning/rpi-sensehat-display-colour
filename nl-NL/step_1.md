+ Typ de volgende code in een Python-bestand:

```python
from sense_hat import SenseHat

sense = SenseHat()

r = 255
g = 255
b = 255

sense.clear((r, g, b))
```

+ Bewaar en voer je code uit. De LED-matrix wordt dan helderwit.

+ De variabelen `r`, `g`en `b` vertegenwoordigen de kleuren rood, groen en blauw. Hun waarden specificeren hoe helder elke kleur moet zijn; elke waarde kan tussen `0` en `255` liggen. In de bovenstaande code is de maximale waarde voor elke kleur gebruikt, dus het resultaat is wit.

+ Je kunt ook alle drie de RGB-waarden van een kleur definiëren met behulp van een enkele coderegel:

```python
red = (255,0,0)
```
 <iframe src="https://trinket.io/embed/python/a588ddedcf" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>

+ Wijzig de waarde van een van de kleuren en voer de code opnieuw uit. Wat zie je?

+ Welke andere kleuren kun je maken?
