## そして...

1. 最後の5行を次のように置き換えます。
    
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

2. コードをもう一度実行します。 さぁ、Sense HATに吹きかけ、笑顔にすることができますか？