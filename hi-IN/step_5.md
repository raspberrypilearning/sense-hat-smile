## और साँस ...

1. आखिरी पांच लाइनों को नीचे दिए गए लाइनों से बदलें:
    
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

2. कोड फिर से चलाएं। अब Sense HAT पर साँस ले और देखे कि क्या आप उसे हंसाने में सक्षम हैं!