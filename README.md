# Trackball12-DIY
For those that want to make their very own trackball using the Raspberry Pi Pico.

3d printer is not required, you can ask a friend or go to your local library to print the shell off. 

Huge thanks to SideraKB, and Wylderbuilds.

![trackMain](https://github.com/user-attachments/assets/427b14f7-e0ad-4de5-964e-e140fccddb44)

## Parts List.

VEICHU Converyor Component VCN310/311 Stainless Steel Round Durable Bull Wheel Transfer Bearing Roller Balls 

Kailh Choc Whites

Choc Keycaps 

Raspberry Pi Pico

Wires 

PMW3360 breakout board (you'll need the sensor as well as the lens if the breakout board doesn't come with one)

M3 heated inserts

8mm-10mm M3 knurled screws 


## Wiring Diagrams:
| PMW3360 Breakout | Pico |
| ----------- | ------ |
| VIN         | 3.3V   |
| GND         | GND    |
| SCLK        | GP18   |
| MOSI        | GP19   |
| MISO        | GP20   |
| CS          | GP21   |
| MOTION      | N/A    |
| RESET       | N/A    |

Whatever pin you choes to be ground, wire all of those to ground. The other pins sould be wired to, from left to right:
GP13, GP12, GP17, GP16

I would recommend making the wires fairly long, so that instalation is easier.

## 3d printed parts.
I had to make the baseplate as simple as I could becasue I had no screws small enough for the pico's screw holes.

On the base plate, the two overhangs might need shaved so that the pico slides under them. The backside may also need shaved a little so that the pico can be put in the hole and held in. The pico is held in by tension, by bending the base plate so that the pico slides into the divot and then stop bending. The pico should now be secured into the base plate.

The micro usb hole may need filed down to fit all micro usb cables, the one that I am using is small enough that I didn't need to.

The heated inserts need to be put in the top half of the body, and the sensor installed with the breakout pins facing to the right.


## Flash command:

`qmk flash -kb trackball -km default`
