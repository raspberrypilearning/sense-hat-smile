## Und atme...

--- task ---

Ersetze die letzten fünf Zeilen durch:

```python
anfangs_feuchtigkeit = sensoren.humidity

while True:
    print(sensoren.humidity)
    if sensoren.humidity > anfangs_feuchtigkeit + 10:
        sensoren.set_pixels(happy)
    elif sensoren.humidity > anfangs_feuchtigkeit + 5:
        sensoren.set_pixels(normal)
    else:
        sensoren.set_pixels(sad)
    sleep(1)
```

--- /task ---

--- task ---

Führe den Code erneut aus. Atme nun auf das Sense-HAT und schau, ob du es zum Lächeln bringen kannst!

--- /task ---


***
Dieses Projekt wurde von freiwilligen Helfern übersetzt:

Karl Schuh

Nicole Rotarius

Helmut Schlimper

Dank freiwilliger Helfer können wir Menschen auf der ganzen Welt die Möglichkeit geben, in ihrer eigenen Sprache zu lernen. Du kannst uns helfen, mehr Menschen zu erreichen, indem Du dich freiwillig zum Übersetzen meldest - weitere Informationen unter [rpf.io/translate](https://rpf.io/translate).