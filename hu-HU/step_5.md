## És lélegezz ...

1. Cserélje ki az utolsó öt sort a következőkkel:
    
    ```python
    start_humidity = sense.humidity while True: print (sense.humidity), ha sense.humidity > start_humidity + 10: sense.set_pixels (boldog) elif sense.humidity > start_humidity + 5: sense.set_pixels (normál) egyéb: sense.set_pixels (szomorú) alvás (1)
    ```

2. Futtassa újra a kódot. Most lélegezzük be a Sense HAT-ot és nézzük meg, hogy mosolyogjon!