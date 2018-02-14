## En adem ...

1. Vervang de laatste vijf regels door:
    
    ```python
start_humidity = sense.humidity while True: print (sense.humidity) if sense.humidity > start_humidity + 10: sense.set_pixels (happy) elif sense.humidity > start_humidity + 5: sense.set_pixels (normaal) anders: sense.set_pixels (sad) sleep (1)
```

2. Voer de code opnieuw uit. Adem nu op de Sense HAT en kijk of je het kunt laten lachen!