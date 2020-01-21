## Tester le Sense HAT

\--- task \---

Ouvre **Mu**, et clique sur l’icône **REPL** et entre la commande qui suit directement dans le REPL :

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Bonjour monde")
```

Appuie sur la touche `Entrée` après chaque ligne. Après la troisième ligne, le message 'Bonjour monde' devrait apparaître sur l'écran du Sense HAT.

\--- /task \---

\--- task \---

Maintenant, essaie de récupérer les valeurs des capteurs :

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

Quand tu appuies sur la touche `Entrée`, tu devrais voir les valeurs des capteurs.

\--- /task \---