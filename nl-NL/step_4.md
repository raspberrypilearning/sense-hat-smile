## En adem ...

\--- task \---

Vervang de laatste vijf regels door:

```python
start_humidity = sense.humidity

while True:
    print(sense.humidity)
    if sense.humidity > start_humidity + 10:
        sense.set_pixels(happy)
    elif sense.humidity > start_humidity + 5:
        sense.set_pixels(normal)
    else:
        sense.set_pixels(sad)
    sleep(1)
```

\---/task\---

\--- task \---

Voer de code opnieuw uit. Adem nu op de Sense HAT en kijk of je het kunt laten lachen!

\--- /task \---