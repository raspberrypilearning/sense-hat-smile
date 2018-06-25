## Et respirez...

1. Remplacez les cinq dernières lignes par:
    
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

2. Exécutez le code à nouveau. Maintenant, respirez près du Sense HAT et voyez si vous pouvez le faire sourire!