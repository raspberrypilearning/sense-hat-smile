## És lélegezz...

\--- task \---

Cseréld le az utolsó öt sort erre:

```python
start_humidity = sense.humidity

while True:
    print(sense.humidity)
    if sense.humidity > start_humidity + 10:
        sense.set_pixels(boldog)
    elif sense.humidity > start_humidity + 5:
        sense.set_pixels(normal)
    else:
        sense.set_pixels(szomoru)
    sleep(1)
```

\--- /task \---

\--- task \---

Futtasd újra a kódot. Most lehelj a Sense HAT-re és nézd meg, hogy meg tudod-e mosolyogtatni!

\--- /task \---