## Sense HATを試す

1. Python 3を開き、以下のコマンドをシェルに直接入力します。
    
    （シェブロンを入力しないでください`>>>`）
    
    ```python
    >>> from sense_hat import SenseHat
    >>> sense = SenseHat()
    >>> sense.show_message("Hello world")
    ```
    
    各行入力後に`Enter`を押してください。 3行目の後、Sense HATのディスプレイに「Hello world」というメッセージが表示されます。

2. 次にセンサー値を取得してみましょう：
    
    ```python
    >>> sense.temperature
    >>> sense.humidity
    >>> sense.pressure
    >>> sense.accelerometer
    >>> sense.gyroscope
    >>> sense.orientation
    ```
    
    `Enter`を押すと、センサーの値が表示されます。