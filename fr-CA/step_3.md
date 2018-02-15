## Tester le Sense HAT

1. Lancez Python 3 à partir du menu principal et entrer les commandes suivantes directement dans l'invite de commande:
    
    (ne tapez pas les chevrons `>>>`)
    
    ```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Bonjour monde!")
```

Appuyez sur `Entrée` après chaque ligne. Après la troisième ligne, le message "Bonjour monde!" devrait apparaître sur l'affichage du Sense HAT.

2. Maintenant, essayez de lire les valeurs des capteurs:
    
    ```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
>>> sense.accelerometer
>>> sense.gyroscope
>>> sense.orientation
```

Lorsque vous appuierez sur `Entrée`, vous verrez les valeurs des capteurs.