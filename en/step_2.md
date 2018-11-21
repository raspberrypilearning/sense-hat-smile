## Test the Sense HAT

--- task ---

Open **Python 3** and enter the following commands directly into the shell:

(do not type the chevrons `>>>`)

```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hello world")
```

Press `Enter` after each line. After the third line, the message 'Hello world' should appear on the Sense HAT's display.

--- /task ---

--- task ---

Now try retrieving the sensor values:

```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
>>> sense.accelerometer
>>> sense.gyroscope
>>> sense.orientation
```

When you press `Enter`, you will see the sensor's value.

--- /task ---
