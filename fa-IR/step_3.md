## Sense HAT را امتحان کنید

1. پایتون 3 را باز کنید و دستورات زیر را مستقیما وارد نمایید:
    
    (این علامت را تایپ نکنید `<<<`)
    
    ```python
    >>> from sense_hat import SenseHat
    >>> sense = SenseHat()
    >>> sense.show_message("Hello world")
    ```
    
    پس از هر خط `Enter` را فشار دهید. بعد از خط سوم، پیام "Hello world" باید بر روی صفحه نمایش Sense HAT ظاهر شود.

2. اکنون مقادیر حسگر را بازیابی کنید:
    
    ```python
    >>> sense.temperature
    >>> sense.humidity
    >>> sense.pressure
    >>> sense.accelerometer
    >>> sense.gyroscope
    >>> sense.orientation
    ```
    
    وقتی `Enter` را فشار دهید، مقدار حسگر را خواهید دید.