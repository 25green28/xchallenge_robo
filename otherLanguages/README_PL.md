# Projekt kontrolera robota x-challange

Projekt zawiera zasoby do wykonania robota RC opartego na arduino i NRF24L01.

> [!NOTE]
> English version is avaiable [here](../README.md).
## Nadajnik - Arduino pro mini

Wyjście / wejście pinów: 
- Cyfrowe
  - Pin 3, Wejście, Przycisk 4
  - Pin 4, Wejście, Przycisk 3
  - Pin 5, Wejscie, Przycisk 2
  - Pin 6, Wejście, Przycisk 1
  - Pin 7, NRF24L01 CE
  - Pin 8, NRF24L01 CSN
  - Pin 11, NRF24L01 MOSI
  - Pin 12, NRF24L01 MISO
  - Pin 13, NRF24L01 SCK
- Analogowe
  - Pin A0, Wejście, Lewy joystick
  - Pin A1, Wejście, Prawy joystick
  - Pin A2, Wejście, Potenciometr

Użyte komponenty
```
Arduino pro mini
NRF24L01
2x Joysticki
4x Przyciski
2x Przetwornice napięcia
```

## Odbiornik - Arduino UNO R3
- Cyforwe
  - Pin 3, Wyjście, RPWM Lewy silnik
  - Pin 6, Wyjście, LPWM Lewy silnik
  - Pin 5, Wyjście, RPWM Lewy silnik
  - Pin 9, Wyjście, LPWM Lewy silnik
  - Pin 11, NRF24L01 MOSI
  - Pin 12, NRF24L01 MISO
  - Pin 13, NRF24L01 SCK
- Analog
  - Pin A0, Wyjście, RPWM Ramię silnik
  - Pin A1, Wyjście, LPWM Ramię silnik
  - Pin A2, Wyjście, RPWM Chwytak silnik
  - Pin A3, Wyjście, LPWM Chwytak silnik

Użyte komponenty
```
Arduino UNO R3
NRF24L01
4x BTS7960
```
