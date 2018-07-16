## Le espressioni facciali

1. Apri una nuova finestra e digita:
    
    ```python
    from sense_hat import SenseHat from faces import normal, happy, sad from time import sleep sense = SenseHat () sense.set_pixels (sad) sleep (1) sense.set_pixels (normal) sleep (1) sense.set_pixels (happy)
    ```

2. Esegui il programma con `F5` e dovresti vedere apparire una faccia triste, una faccia normale e una faccia felice.