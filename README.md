# victoria_electrical
Place to house all electrical system components diagram, BOMs, etc.

# Motor Encoder Color Mapping
The wires from the drive motors were extended.
The wire color mapping to the new cable is:

| Signal | Motor Side    | Board Side    |
|:------:|:-------------:|:-------------:|
| VCC    | Orange        | Red           |
| GND    | Green         | Brown         |
| Ch A   | Yellow        | Yellow        |
| Ch B   | Brown         | Orange        |

The encoder `Vcc` has a range from 2.4V - 26V, but is currently connected to 5V.
