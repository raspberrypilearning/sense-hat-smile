## Gezichten

1. Open een nieuw venster en typ:
    
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

2. Voer de code uit met `F5` en je zou een droevig gezicht, een normaal gezicht en een blij gezicht moeten zien verschijnen.