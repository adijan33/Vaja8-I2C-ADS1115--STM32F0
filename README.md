# Vaja8-I2C-ADS1115--STM32F0

2.c
V kategoriji Connectivity izberite in omogočite I2C komunikacijo. Kateri pini se aktivirajo? PB6 in PB7. 
Koliko različnih I2C komunikacij vaša razvojna plošča omogoča? Dve.

e.
| ADS1115 | STM32F0 | Opomba |
|---------|----------|-----------|
| SCL     | PB6      | I²C clock |
| SDA     | PB7      | I²C data  |
| ADDR    |          | naslovni pin |
| ALRT    | (ni povezan) | ni uporabljen |
| VDD     | 5 V ali 3.3 V | napajanje |

f.
V Parameter Settings protokola I2C spremenite Speed Mode na Fast. Koliko znaša sedaj frekvenca?


Pinout:
<img width="538" height="541" alt="image" src="https://github.com/user-attachments/assets/514ed747-d033-4f6e-b8f2-f10441537241" />


