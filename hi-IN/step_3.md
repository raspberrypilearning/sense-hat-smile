## Sense HAT का परीक्षण करें

1. Python 3 खोलें और शेल में सीधे निम्नलिखित कमांड दर्ज करें:
    
    (चेवर्ण टाइप न करें `>>>`)
    
    ```python
    >>> from sense_hat import SenseHat
    >>> sense = SenseHat()
    >>> sense.show_message("Hello world")
    ```
    
    प्रत्येक पंक्ति के बाद `Enter` दबाए। तीसरी पंक्ति के बाद, 'Hello world' संदेश Sense HAT की डिस्प्लेय पर दिखाई देना चाहिए।

2. अब सेंसर मूल्यों को पुनः प्राप्त करने का प्रयास करें:
    
    ```python
    >>> sense.temperature
    >>> sense.humidity
    >>> sense.pressure
    >>> sense.accelerometer
    >>> sense.gyroscope
    >>> sense.orientation
    ```
    
    `Enter` दबाने के पश्च्यात, आप सेंसर मूल्य देख सकेंगे।