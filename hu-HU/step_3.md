## Arcok

\--- task \---

Zárd be a REPL-t és írd be a következőt a főablakba:

```python
from sense_hat import SenseHat
from faces import normal, boldog, szomoru
from time import sleep

sense = SenseHat()

sense.set_pixels(szomoru)
sleep(1)
sense.set_pixels(normal)
sleep(1)
sense.set_pixels(boldog)
```

\--- /task \---

\--- task \---

Futtasd a kódot az **F5** lenyomásával és látnod kell egy szomorú, egy semleges és egy boldog arcot megjelenni.

\--- /task \---