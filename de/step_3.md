## Teste die Sense-HUT

1. Öffne Python 3 und gib die folgenden Befehle direkt in die Shell ein:
    
    (Bitte nicht die Chevrons eingeben `>>>`)
    
    ```python
>>> von sense_hat import SenseHat>>> sense = SenseHat ()>>> sense.show_message ("Hallo Welt")
```

Drücken Sie `Enter` nach jeder Zeile. Nach der dritten Zeile sollte die Meldung "Hello world" auf dem Display des Sense HAT erscheinen.

2. Versuchen Sie nun, die Sensorwerte abzurufen:
    
    ```python
>>> Sinn.Temperatur>>> Sinn.Feuchte>>> Sinndruck>>> sense.accelerometer>>> sense.gyroscope>>> Sinnorientierung
```

Wenn Sie `Enter`drücken, sehen Sie den Wert des Sensors.