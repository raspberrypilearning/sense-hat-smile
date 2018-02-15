## Visages

1. Ouvrez un nouveau fichier Python et tapez:
    
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

2. Exécutez le code avec `F5` et vous devriez voir un visage triste, un visage normal, et un visage heureux apparaît.