## و نفس بکشید...

1. آخرین پنج خط را با دستورهای زیر جایگزین کنید:
    
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

2. دوباره کد را اجرا کنید. حال بر روی HAT Sense نفس بکشید و ببینید آیا می‌توانید کاری کنید که لبخند بزند!