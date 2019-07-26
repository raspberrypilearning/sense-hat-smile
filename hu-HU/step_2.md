## Teszteld a Sense HAT-et

\--- task \---

Nyisd meg a **Mu**-t, kattints a **REPL** ikonra és add meg a következő parancsot közvetlenül a REPL-be:

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Hello világ")
```

Üss `Enter`-t minden sor után. A harmadik sor után, a 'Hello világ' üzenetnek kell megjelennie a Sense HAT kijelzőjén.

\--- /task \---

\--- task \---

Most próbáld meg lekérdezni az érzékelő értékeit:

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

Miután megnyomod az `Enter`-t, láthatod az érzékelő értékeit.

\--- /task \---