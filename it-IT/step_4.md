## Le espressioni facciali

1. Apri una nuova finestra e digita:
    
    ```python
da sense_hat import SenseHat da facce import normale, felice, triste da tempo import sleep sense = SenseHat () sense.set_pixels (triste) sleep (1) sense.set_pixels (normale) sleep (1) sense.set_pixels (happy)
```

2. Esegui il programma con `F5` e dovresti vedere apparire una faccia triste, una faccia normale e una faccia felice.