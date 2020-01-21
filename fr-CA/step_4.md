## Et respirez...

\--- task \---

Remplace les cinq dernières lignes avec :

```python
start_humidity = sense.humidity

while True:
    print(sense.humidity)
    if sense.humidity > start_humidity + 10:
        sense.set_pixels(content)
    elif sense.humidity > start_humidity + 5:
        sense.set_pixels(normal)
    else:
        sense.set_pixels(triste)
    sleep(1)
```

\--- /task \---

\--- task \---

Exécute le code à nouveau. Maintenant, respire près du Sense HAT et voit si tu peux le faire sourire!

\--- /task \---