## Prova il Sense HAT

1. Apri Python 3 e inserisci i seguenti comandi direttamente nel shell:
    
    (non digitare i simboli di *maggiore* `>>>`)
    
    ```python
    >>> from sense_hat import SenseHat
    >>> sense = SenseHat()
    >>> sense.show_message("Buongiorno")
    ```
    
    Premi il tasto `Invio` dopo ogni riga. Dopo la terza riga, il messaggio "Hello world" dovrebbe apparire sul display del Sense HAT.

2. Ora prova a recuperare i valori del sensore:
    
    ```python
    >>> sense.temperature
    >>> sense.humidity
    >>> sense.pressure
    >>> sense.accelerometer
    >>> sense.gyroscope
    >>> sense.orientation
    ```
    
    Quando premerai `Invio`, vedrai i valori del sensore.