## Visages

\--- task \---

Ferme de REPL et tape ce qui suit dans la fenêtre principale:

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

Exécute de code avec **F5** et tu devrais voir un visage triste, un visage normal et un visage heureux apparaitre.

\--- /task \---