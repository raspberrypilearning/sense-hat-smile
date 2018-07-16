## چهره‌ها

1. یک پنجره جدید باز کنید و تایپ کنید:
    
    ```python
    from sense_hat import SenseHat
    from faces import normal, happy, sad
    from time import sleep
    
    sense = SenseHat()
    
    sense.set_pixels(sad)
    sleep(1)
    sense.set_pixels(normal)
    sleep(1)
    sense.set_pixels(happy)
    ```

2. با فشردن `F5` کد را اجرا کنید و می‌بینید که یک چهره‌ی غمگین، یک چهره‌ی طبیعی و یک چهره‌ی خوشحال ظاهر می شود.