## Sense HAT का परीक्षण करें

\--- task \---

Open **Mu**, click the **REPL** icon and enter the following commands directly into the REPL:

```python
from sense_hat import SenseHat
sense = SenseHat()
sense.show_message("Hello world")
```

प्रत्येक पंक्ति के बाद `Enter` दबाए। तीसरी पंक्ति के बाद, 'Hello world' संदेश Sense HAT की डिस्प्लेय पर दिखाई देना चाहिए।

\--- /task \---

\--- task \---

अब सेंसर मूल्यों को पुनः प्राप्त करने का प्रयास करें:

```python
sense.temperature
sense.humidity
sense.pressure
sense.accelerometer
sense.gyroscope
sense.orientation
```

`Enter` दबाने के पश्च्यात, आप सेंसर मूल्य देख सकेंगे।

\--- /task \---