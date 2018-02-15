## Test de Sense HAT

1. Open Python 3 en voer de volgende opdrachten rechtstreeks in de shell in:
    
    (typ niet de chevrons `>>>` in)
    
    ```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hallo wereld")
```

Druk op `Enter` na elke regel. Na de derde regel verschijnt het bericht 'Hallo wereld' op het scherm van de Sense HAT.

2. Probeer nu de sensorwaarden op te halen:
    
    ```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
>>> sense.accelerometer
>>> sense.gyroscope
>>> sense.orientation
```

Wanneer je op `Enter`drukt, zie je de waarde van de sensor.