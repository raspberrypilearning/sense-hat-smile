## Und atme ...

1. Ersetze die letzten fünf Zeilen durch:
    
    ```python
start_humidity = sensoren.humidity

while True:
    print(sensoren.humidity)
    if sensoren.humidity > start_humidity + 10:
        sensoren.set_pixels(happy)
    elif sensoren.humidity > start_humidity + 5:
        sensoren.set_pixels(normal)
    else:
        sensoren.set_pixels(sad)
    sleep(1)
```

2. Führe den Code erneut aus. Atme nun auf das Sense-HAT und schau, ob du es zum Lächeln bringen kannst!