# humidity-temperature-monitor
Humidity and Temperature Monitoring System using Arduino UNO

## This project uses an Arduino with:
- DHT11 temperature & humidity sensor
- 1602A LCD display

 ## Features
- Shows temperature and humidity on LCD
- Real-time monitoring

 ## Hardware
- Arduino Uno
- DHT11(humidity-temperature sensor)
- 16x2 LCD (1602A)
- 10k potentiometer

## Wiring
for the LCD:
GND TO GND 
VCC or VDD TO 5V
RS TO PIN 7
VO TO 10k potentiometer (MID PIN)
RW TO GND 
E TO PIN 8
from D0-D3 not used 
D4 TO PIN 9
D5 TO PIN 10
D6 TO PIN 11
D7 TO PIN 12
BLA TO V5
BLK TO GND

for the 10k potentiometer:
right PIN TO GND
MID PIN TO VO (LCD)
left PIN TO 5V

for the DHT (humidity + temperature):
left(S) PIN TO PIN 2
MID PIN (+) TO 5V
right(-) PIN TO GND

## Libraries used
- DHT sensor library
- LiquidCrystal
