## En adem ...

--- task ---

Vervang de laatste vijf regels door:

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

--- /task ---

--- task ---

Voer de code opnieuw uit. Adem nu op de Sense HAT en kijk of je het kunt laten lachen!

--- /task ---


**Door de community geleverde vertaling**

Dit project werd vertaald door **Cor Groot**/**Coen Warries** en gecontroleerd door **Bino Maiheu**/**Robert-Jan Kempenaar**.

Onze geweldige vertalers helpen ons om kinderen over de hele wereld de kans te geven te leren coderen. Jij kunt ons helpen nog meer kinderen te bereiken door onze projecten te vertalen - lees meer op [rpf.io/translators](https://rpf.io/translators).