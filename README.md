# Trackball12-DIY
For those that want to make their very own trackball using the Raspberry Pi Pico.

3d printer is not required, you can ask a friend or go to your local library to print the shell off. 

Huge thanks to SideraKB, and Wylderbuilds.

![trackMain](https://github.com/user-attachments/assets/427b14f7-e0ad-4de5-964e-e140fccddb44)

**Parts List.**
VEICHU Converyor Component VCN310/311 Stainless Steel Round Durable Bull Wheel Transfer Bearing Roller Balls 
Kailh Choc Whites
Choc Keycaps 
Raspberry Pi Pico
Wires 
PMW3360 breakout board (you'll need the sensor as well as the lens if the breakout board doesn't come with one)
M3 heated inserts
8mm-10mm M3 knurled screws 

Wiring Diagrams:
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

Flash command:

`qmk flash -kb trackball -km default`
