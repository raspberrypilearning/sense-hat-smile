## Visages

\--- task \---

Ferme le REPL et écrit ce qui suit dans la fenêtre principale :

```python
from sense_hat import SenseHat
from faces import normal, content, triste
from time import sleep

sense = SenseHat()

sense.set_pixels(triste)
sleep(1)
sense.set_pixels(normal)
sleep(1)
sense.set_pixels(content)
```

\--- /task \---

\--- task \---

Exécute le code en appuyant sur la touche **F5** et tu devrais voir apparaître un visage triste, suivi d'un visage normal, suivi d'un visage content.

\--- /task \---