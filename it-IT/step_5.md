## E respira...

1. Sostituisci le ultime cinque righe con:
    
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

2. Esegui nuovamente il programma. Ora alita sul Sense HAT e vedi se riesci a farlo sorridere!