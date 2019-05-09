## And breathe...

\--- task \---

Replace the last five lines with:

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

\--- /task \---

\--- task \---

Run the code again. Now breathe on the Sense HAT and see if you can make it smile!

\--- /task \---