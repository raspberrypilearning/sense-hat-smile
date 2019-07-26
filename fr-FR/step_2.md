## Tester le Sense HAT

\--- task \---

Ouvre **Mu**, clique sur l'icone **REPL** et entre la commande suivante directement dans le REPL:

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Bonjour tout le monde")
```

Appuie sur `Entrer` après chaque ligne. Après la troisième ligne, le message 'Bonjour le monde' devrait apparaître sur l'écran du Sense HAT.

\--- /task \---

\--- task \---

Maintenant essaie de récupérer les valeurs des capteurs:

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

Lorsque tu appuies sur `Entrer`, tu vas voir la valeur du capteur.

\--- /task \---