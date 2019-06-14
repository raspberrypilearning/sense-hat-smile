## चेहरे

\--- task \---

Close the REPL and type the following into the main window:

```python
from sense_hat import SenseHat
from faces import normal, happy, sad
from time import sleep

sense = SenseHat()

sense.set_pixels(sad)
sleep(1)
sense.set_pixels(normal)
sleep(1)
sense.set_pixels(happy)
```

\--- /task \---

\--- task \---

**F5** दबाकर कोड चलाने के पश्च्यात आपको एक उदास चेहरे, एक सामान्य चेहरे और एक प्रसन्न चेहरा दिखाई देना चाहिए।

\--- /task \---