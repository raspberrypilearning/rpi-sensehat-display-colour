+ एक python file में, निम्न कोड टाइप करें:

```python
from sense_hat import SenseHat

sense = SenseHat()

r = 255
g = 255
b = 255

sense.clear((r, g, b))
```

+ अपना कोड सहेजें और चलाएं। तब फिर LED matrix चमकदार सफेद हो जाएगा।

+ `r`, `g`, और `b` variables लाल, हरे और नीले रंग का प्रतिनिधित्व करते हैं। उनके मूल्य यह निर्दिष्ट करते हैं कि प्रत्येक रंग कितना उज्ज्वल होना चाहिए; प्रत्येक मूल्य `0` तथा `255` के बीच हो सकता है। उपरोक्त code में, प्रत्येक रंग के लिए अधिकतम मूल्य का उपयोग किया गया है, इसलिए परिणाम सफेद है।

+ आप code की एक पंक्ति लिख कर भी रंगों की तीनो RGB मूलो को भी परिभाषित कर सकते हैं.

```python
red = (255,0,0)
```
 <iframe src="https://trinket.io/embed/python/a588ddedcf" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>

+ रंगों में से किसी एक का मूल्य बदलें, उसके बाद code फिर से चलाएँ। आप क्या देख पा रहे हैं?

+ आप कौन से अन्य रंग बना सकते हैं?
