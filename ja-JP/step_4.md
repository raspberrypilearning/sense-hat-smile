## 顔

1. 新しいウィンドウを開き、以下のように入力します。
    
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

2. `F5`でコードを実行します。悲しい顔、普通の顔、そして幸せな顔が現れるはずです。