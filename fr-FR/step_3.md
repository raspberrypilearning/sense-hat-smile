## Testez le Sense HAT

1. Ouvrez Python 3 et entrez les commandes suivantes directement dans le shell:
    
    (ne pas taper les chevrons `>>>`)
    
    ```python
    >>> à partir de sense_hat importez SenseHat>>> sens = SenseHat ()>>> sense.afficher_message ("Bonjour le monde")
    ```
    
    Appuyez sur `Entrée` après chaque ligne. Après la troisième ligne, le message 'Bonjour le monde' devrait apparaître sur l'écran de Sense HAT.

2. Essayez maintenant de récupérer les valeurs du capteur:
    
    ```python
    >>> sense.temperature>>> sens.humidité>>> sens.pression>>> sense.acceléromètre>>> sense.gyroscope>>> sense.orientation
    ```
    
    Lorsque vous appuyez sur `Entrée`, vous voyez la valeur du capteur.