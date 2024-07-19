# Trackball12-DIY
For those that want to make their very own trackball using the Raspberry Pi Pico.

Huge thanks to SideraKB, and Wylderbuilds.

![trackMain](https://github.com/user-attachments/assets/fd65c165-c9ba-4327-9af1-bbb833a196fd)

Wiring Diagrams:
| PMW3360 Breakout | Pico |
| ----------- | ------ |
| VIN         | 3.3V   |
| GND         | GND    |
| SCLK        | GP22   |
| MOSI        | GP23   |
| MISO        | GP20   |
| CS          | GP21   |
| MOTION      | --     |
| RESET       | --     |

Flash command.
`qmk flash -kb trackball -km default`
