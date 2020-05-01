## Gesichter

--- task ---

Schließe REPL und tippe das Folgende in das Hauptfenster:

```python
from sense_hat import SenseHat
from faces import normal, happy, sad
from time import sleep

sensoren = SenseHat()

sensoren.set_pixels(sad)
sleep(1)
sensoren.set_pixels(normal)
sleep(1)
sensoren.set_pixels(happy)
```

--- /task ---

--- task ---

Führe den Code mit **F5** aus und du solltest ein trauriges Gesicht, ein normales Gesicht und ein glückliches Gesicht sehen.

--- /task ---