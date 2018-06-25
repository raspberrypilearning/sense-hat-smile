## センスHATをテストする

1. Python 3を開き、次のコマンドをシェルに直接入力します。
    
    （シェブロンを入力しないでください`>>>`）
    
    ```python
>>> sense_hatからのインポートSenseHat>>> sense = SenseHat（）>>> sense.show_message（ "Hello world"）
```

プレス`入力`各行の後に。 3行目の後、Sense HATのディスプレイに「Hello world」というメッセージが表示されます。

2. 次にセンサー値を取得してみましょう：
    
    ```python
>>> sense.temperature>>> sense.humidity>>> sense.pressure>>> sense.accelerometer>>> sense.gyroscope>>>センス。オリエンテーション
```

`Enter`を押すと、センサーの値が表示されます。