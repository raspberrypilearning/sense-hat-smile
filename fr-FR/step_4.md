## Et respire...

\--- task \---

Remplace les cinq dernières lignes par:

```python
humidite_de_depart = sense.humidity

while True:
    print(sense.humidity)
    if sense.humidity > humidite_de_depart + 10:
        sense.set_pixels(happy)
    elif sense.humidity > humidite_de_depart + 5:
        sense.set_pixels(normal)
    else:
        sense.set_pixels(sad)
    sleep(1)
```

\--- /task \---

\--- task \---

Exécute le code à nouveau. Maintenant respire sur le Sense HAT et regarde si tu peux le faire sourire!

\--- /task \---