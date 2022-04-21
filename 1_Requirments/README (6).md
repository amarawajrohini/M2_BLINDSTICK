
## Introduction
The paper presents a theoretical model and a system concept to provide a smart electronic aid for blind people. 
This Project is aimed to aid the blind people and enabling them to analyse and judge the environment by the use of the ultrasonic sensors. the blind man can easily detect and differentiate the things/obstacles from irregularities of the roads like pits and other things. If there’s an obstacle in front of the blind man the vibratory circuit gets activated and if there’s any irregularity in the road the buzzer gets activated. And the all these sensors and indicating element are controlled via an Arduino mega. In this project we are using one Arduino, Ultrasonic senor, buzzer ,vibration motor and switch.




## Research
an innovative stick designed for visually disabled people for improved navigation. We here propose an advanced blind stick that allows visually challenged people to navigate with ease using advanced technology. 

## SWOT analysis

STRENGHTS - Have good knowledge in programming a Arduino to make a smart blind cane.  The price is affordable. Have more experience in business field.

 WEAKNESS-Time:Only the founder must do it alone  Limited: The buyers are limited.


 OPPORTUNITIES- Easy partnership Can easily promote product to blinds at their home ,Can be develop to a national level

 THREATS- Hard to gain the loyalty from customer.Many competitor with competitive price ,A lot of competitors in the market with similar products



 

 
## 4'W AND 1'H

4'W AND 1'Hard

WHO-blind people

WHAT- Smart blind stick

WHERE- streets,grounds, walking areas etc

WHEN- while walking

HOW- by using elements like sensors, buzzer,led etc
## Low level requirments

TECH SPECS
Microcontroller ATmega328,
Operating voltage 5v,
Input voltage 7-12v(recommended),
Input voltage 6-20v(limits),
Digital I/O pins 54 (of which 14 provide PWM output),
Analog input pins 16,
Dc current per I/O pin 40mA,
Dc current for 3.3v pin 50mA, 
Flash Memory 256kb of which 8kb used by bootloader ,
SRAM 8kb,
EEPROM 4KB,
clock speed 16 MHz,

Serial: 0 (RX) and 1 (TX); Seria} 1:19 (RX)
and 16 (TX); Serial 3: 15 (RX) and 14 (TX). Used to receive (Rx
transmit (TX) TTL serial data. Pins 0 and 1 are also one ee
corresponding pins of the ATmega328  USB-to-TTL Serial chip. 



External Interrupts: 2 (interrupt 0), 3 (interrupt 1), 18 (interrupt 5)
19 (interrupt 4), 20 (interrupt 3), and 21 (interrupt 2). These pins on
be configured to trigger an interrupt on alow value, a rising or falling
edge, or a change in value. See the attachInterrupt() function for
details.

PWM: 0 to 13. Provide 8-bit PWM Output with the analogWrite()
function.

SPI: 50 (MISO), 51 (MOSI), 52 (SCK), 53 (SS). These pins support SPI
communication using the SPI library. The SPI pins are also broken
out on the ICSP header, which is physically compatible with the Uno,
Duemilanove and Diecimila.

LED: 13. There is a built-in LED connected to digital pin 13. When the
pin is HIGH value, the LED is on, when the pin is LOW, it's off.

TWI: 20 (SDA) and 21 (SCL). Support TW! communication using a
Wire library. Note that these pins are not in the same location as
TWI pins on the Duemilanove or Diecimila.

Ultrasonic sensors emit short, high-frequency sound pulses at regular intervals. These propagate in the air at the velocity of sound. If they strike an object, then they are reflected back as echo signals to the sensor, which itself computes the distance to the target based on the time-span between emitting the signal and receiving the ehco.

. Operating voltage: +5V

. Theoretical Measuring Distance: 2cm to 450cm

. Practical Measuring Distance: 2cm to 80cm

Accuracy: 3mm

. Measuring angle covered: <15°

. Operating Current: <15mA

Operating Frequency: 40kHz

## High level requirments

Main requirment is to avoid and detect obstacles with robots like biped robot, obstacle avoider robot, path finding robot etc
and used to measure the distance within a wide range of 2cm to 400cm
, can be used to map the objects surrounding the sensor by rotating it, depth of certain places like wells, pits etc can be measured since the waves can penetracte through wate   

The arduino atmega328 has a resettable polyfuse that protects your computer's USB ports from shorts and overcurrent.
although most computers provide their own internal protection , the fuse provides a extra layer of protection. if more than 50mA is applied  to the USB port, the fuse will automatically break the connection until the short or overload is removed.

