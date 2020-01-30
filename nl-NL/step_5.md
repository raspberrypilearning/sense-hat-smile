## En adem ...

1. Vervang de laatste vijf regels door:
    
    ```python
    start_humidity = sense.humidity
    
    while True:
        print(sense.humidity)
        if sense.humidity > start_humidity + 10:
            sense.set_pixels(happy)
        elif sense.humidity > start_humidity + 5:
            sense.set_pixels(normal)
        else:
            sense.set_pixels(sad)
        sleep(1)
    ```

2. Voer de code opnieuw uit. Adem nu op de Sense HAT en kijk of je het kunt laten lachen!


***
Dit project werd vertaald door vrijwilligers:

Coen Warries

Robert-Jan Kempenaar

Cor Groot

Bino Maiheu

Dankzij vrijwilligers kunnen we mensen over de hele wereld de kans geven om in hun eigen taal te leren. Jij kunt ons helpen meer mensen te bereiken door vrijwillig te starten met vertalen - meer informatie op [rpf.io/translate](https://rpf.io/translate).