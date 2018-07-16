## Teste das Sense-HAT

1. Öffne Python 3 und gib die folgenden Befehle direkt in die Shell ein:
    
    (Bitte die Größer-Zeichen nicht eingeben `>>>`)
    
    ```python
    >>> from sense_hat import SenseHat
    >>> sensoren = SenseHat()
    >>> sensoren.show_message("Hallo Welt")
    ```
    
    Drücke am Ende jeder Zeile `Enter`. Nach der dritten Zeile sollte die Meldung "Hallo Welt" auf dem Display des Sense HAT erscheinen.

2. Versuche nun, die Sensorwerte abzurufen:
    
    ```python
    >>> sensoren.temperature
    >>> sensoren.humidity
    >>> sensoren.pressure
    >>> sensoren.accelerometer
    >>> sensoren.gyroscope
    >>> sensoren.orientation
    ```
    
    Wenn du `Enter` drückst, siehst du den Wert des Sensors.