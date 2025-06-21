# DIY-ESP32-DIV

Softwares:
Arduino IDE 1.8.19
Board Managers:  must Install ESP32 versi 2.0.11
Use Provided Libraries. Replace your existing ones


TFT-IL9431
------
TFT_MISO 12
TFT_MOSI 13
TFT_SCLK 14
TFT_CS   15  
TFT_DC    2  
TFT_RST  EN 
T_CS    33
T_IRQ   34
T_MOSI  32
T_MISO  35
T_CLK   25

CC1101 HW863
------
CSN 27
SCK 18
MOSI 23
GOD0 26
GOD1 19
GOD2 16

        NRF 1      NNR2
CE        4           16
CSN       5           17
SCK      18           18
MOSI     23           23
MISO     19           19
IRQ     --- not used ---

PCF8574 (GPIO Extender Module)
SDA 21
SCL 22
VCC 5V
GND GND

Button (These pins are in the PCF8574)
BTN_UP     P6
BTN_DOWN   P3
BTN_LEFT   P4
BTN_RIGHT  P5
BTN_SELECT P7
