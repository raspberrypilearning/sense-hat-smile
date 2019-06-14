## Teste das Sense-HAT

\--- task \---

Open **Mu**, click the **REPL** icon and enter the following commands directly into the REPL:

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Hello world")
```

Drücke `Enter` am Ende jeder Zeile. Nach der dritten Zeile sollte die Meldung "Hallo Welt" auf dem Display des Sense HAT erscheinen.

\--- /task \---

\--- task \---

Versuche nun, die Sensorwerte abzurufen:

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

Wenn du `Enter` am Ende der Zeile drückst, siehst du den Wert des Sensors.

\--- /task \---