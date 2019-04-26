# RC-car
WiFi enabled RC car using ESP8266 with Motorsield and Blynk

## Libraries
- blynk
- Adafruit Motorsield library V1
- ESP8266WiFi

## Problems
- Motorshield in hand is by DK-Electronics and used Adafruit motorshield library v1.
- Adafruit motorshield library v1 only works with Arduino UNO etc. and not with ESP8266 boards

### Possible solutions
- Use ATmega2560 + ESP8266 board.
- Connect ESP8266 to UNO with the motorshield on.
- Create a H-brigde to control the DC motors.
- Use PWM to control the DC motors.

## Before programming
- [Install ESP8266 drivers and install boards to Arduino IDE](https://learn.adafruit.com/adafruit-io-basics-esp8266-arduino/using-arduino-ide)

## Resources
- [Blynk website](https://blynk.io/en/getting-started)
- [Install Blynk to Arduino IDE](https://github.com/blynkkk/blynk-library/releases/tag/v0.6.1) or just find 'Blynk' in the Arduino library manager
- [ESP8266 RC-car guide](https://www.hackster.io/andrewf1/simplest-wifi-car-using-esp8266-motorshield-37501e)
- Using DK Electronics motorshield based on [Adafruit V1 Motor shield](https://learn.adafruit.com/adafruit-motor-shield/overview)
- DK Electronics motoshield [forum discussion](https://forum.arduino.cc/index.php?topic=211225.0)
- [DK-electronics motorshield describtion](https://impremedia.net/dk-electronics-arduino-motor-shield/)

### Saved links
- [DC motor sspeed control using Adruino PWM](https://duino4projects.com/dc-motor-speed-control-using-arduino-pwm/)
- [Banggood link to Atmega + ESP8266 board](https://community.blynk.cc/t/wemos-mega-wifi-r3-atmega2560-esp8266/19626)
- [MEGA+WiFi R3 ATmega2560+ESP8266, flash 32MB, USB-TTL CH340G, Micro-USB](https://robotdyn.com/mega-wifi-r3-atmega2560-esp8266-flash-32mb-usb-ttl-ch340g-micro-usb.html)
- [discussion about Motorshield on the mega](https://forums.adafruit.com/viewtopic.php?t=34840)
- [Adafruit store page for motorshield v2](https://www.adafruit.com/product/1438)
- [Arduino PWM tutorial](https://www.arduino.cc/en/Tutorial/PWM)
- [Add WiFi to Arduino UNO with ESP8266](https://www.instructables.com/id/Add-WiFi-to-Arduino-UNO/)
- [Install Adafruit motorshield v2](https://learn.adafruit.com/adafruit-stepper-dc-motor-featherwing/arduino-usage)
- [Adafruit motorshield v2 library](https://github.com/adafruit/Adafruit_Motor_Shield_V2_Library)
- [Adafruit motorshield v1 page](https://learn.adafruit.com/adafruit-motor-shield/overview)
- [DC motor WiFi car](https://drive.google.com/drive/folders/1sCQeuDMOKSQRO44lZ76piK6KbpfwH5So)
- [Blynk Arduino library](https://github.com/blynkkk/blynk-library/releases/)
- [Motorize IoT With ESP8266](https://www.instructables.com/id/Motorize-IoT-With-ESP8266/)
- [Adafruit motorshield guide](http://www.robotshop.us/media/files/PDF/adafruit-motor-shield-arduino-user-guide.pdf)
- [DK-electronics guides](https://impremedia.net/dk-electronics-arduino-motor-shield/)
- [DK electronics motorshield schematic](https://forum.arduino.cc/index.php?action=dlattach;topic=211225.0;attach=71519)
