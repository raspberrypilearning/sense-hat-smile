## Prova il CAPO SENSIBILE

1. Apri Python 3 e inserisci i seguenti comandi direttamente nella shell:
    
    (non digitare le frecce `>>>`)
    
    ```python
>>> da sense_hat import SenseHat>>> sense = SenseHat ()>>> sense.show_message ("Hello world")
```

Premere `Invio` dopo ogni riga. Dopo la terza riga, il messaggio "Hello world" dovrebbe apparire sul display di Sense HAT.

2. Ora prova a recuperare i valori del sensore:
    
    ```python
>>> sense.temperature>>> sense.humidity>>> sense.pressure>>> sense.accelerometer>>> sense.gyroscope>>> sense.orientation
```

Quando premi `Invio`, vedrai il valore del sensore.