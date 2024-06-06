# Controller project for x-challange robot

Project contains resources, to make RC robot based on arduino and NRF24L01.

> [!NOTE]
> Polish version is avaiable [here](otherLanguages/README_PL.md).

## Transmitter - Arduino pro mini

Pinout 
- Digital
  - Pin 3, INPUT, Button 4
  - Pin 4, INPUT, Button 3
  - Pin 5, INPUT, Button 2
  - Pin 6, INPUT, Button 1
  - Pin 7, NRF24L01 CE
  - Pin 8, NRF24L01 CSN
  - Pin 11, NRF24L01 MOSI
  - Pin 12, NRF24L01 MISO
  - Pin 13, NRF24L01 SCK
- Analog
  - Pin A0, INPUT, Left Joystick
  - Pin A1, INPUT, Right Joystick
  - Pin A2, INPUT, PotentiometerPin

Used components
```
Arduino pro mini
NRF24L01
2x Joysticks
4x Buttons
2x Voltage converters
```

## Reciver - Arduino UNO R3
- Digital
  - Pin 3, OUTPUT, RPWM Left Motor
  - Pin 6, OUTPUT, LPWM Left Motor
  - Pin 5, OUTPUT, RPWM Right Motor
  - Pin 9, OUTPUT, LPWM Right Motor
  - Pin 11, NRF24L01 MOSI
  - Pin 12, NRF24L01 MISO
  - Pin 13, NRF24L01 SCK
- Analog
  - Pin A0, OUTPUT, RPWM Arm Motor
  - Pin A1, OUTPUT, LPWM Arm Motor
  - Pin A2, OUTPUT, RPWM Gripper Motor
  - Pin A3, OUTPUT, LPWM Gripper Motor
 

Used components
```
Arduino UNO R3
NRF24L01
4x BTS7960
```
