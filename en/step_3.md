## Faces

--- task ---

Close the REPL and type the following into the main window:

```python
from sense_hat import SenseHat
from faces import normal, happy, sad
from time import sleep

sense = SenseHat()

sense.set_pixels(sad)
sleep(1)
sense.set_pixels(normal)
sleep(1)
sense.set_pixels(happy)
```

--- /task ---

--- task ---

Run the code with **F5** and you should see a sad face, a normal face, and a happy face appear.

--- /task ---
