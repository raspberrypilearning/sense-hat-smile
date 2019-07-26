## Test de Sense HAT

--- task ---

Open **Mu**, klik op het **REPL** pictogram en typ de volgende commands direct in de REPL:

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Hallo wereld")
```

Druk op `Enter` na elke regel. Na de derde regel verschijnt het bericht 'Hallo wereld' op het scherm van de Sense HAT.

--- /task ---

--- task ---

Probeer nu de sensorwaarden op te halen:

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

Wanneer u op `Enter` drukt, ziet u de waarde van de sensor.

--- /task ---