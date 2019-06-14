## Und atme ...

\--- task \---

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

\--- /task \---

\--- task \---

Führe den Code erneut aus. Atme nun auf das Sense-HAT und schau, ob du es zum Lächeln bringen kannst!

\--- /task \---