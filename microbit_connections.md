micro:bit connections
=====================
You will find some differences among the multiples versions of _hub75_ matrices, but the connector is the same. Some matrices use R1, R2, G1, G2, B1, B2 instead of R0, R1, G0, G1, B0, B1.

| micro:bit | hub75 matrix |
|:-:|:-:|
| P6 | OE |
| P7 | STB/LAT |
| P8 | C |
| P9 | B |
| P10 | A |
| P12 | D |
| P13 | CLK |
| P15 | R0 |
| GND | GND |

Additionally you need to connect some pins from the left, to the right one.

| left connector | right connector |
|:-:|:-:|
| R1 | R0 |
| G1 | G0 |
| B1 | B0 |
| G0 | R1 |
| B0 | G1 |


The pins on the connector are (it could rotated):

|  |  |
|:-:|:-:|
| R0 | G0 |
| B0 | GND |
| R1 | G1 |
| B1 | GND |
| A | B |
| C | D |
| CLK | LAT |
| OE | GND |



DS3231 connections

| DS3231 | micro:bit (sensor:bit) |
|:-:|:-:|
| GND | G |
| VCC | V |
| SDA | DA |
| SCL | CL |
