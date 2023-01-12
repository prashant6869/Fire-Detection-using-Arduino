# Fire-Detection-using-Arduino

circuit diagram of the project (Link):-

(https://user-images.githubusercontent.com/99020701/212127456-ab111fee-1bc7-4a58-9572-7fbb3b582ce2.png)

(https://user-images.githubusercontent.com/99020701/212127744-38862b98-f427-4381-9e52-59fb2ad74ae9.png)



Problem statement:
Safety is a crucial consideration in the design of residential and commercial buildings to safeguard against the loss of life and damage to property. 
The existing fire alarm system on market nowadays is too complex in terms of its design and structure. Since the system is too complex, 
it needs regular maintenance to be carried out to make sure the system operates well. Meanwhile, when the maintenance is being done to the existing system,
it could raise the cost of the system
Introduction:

Domain:
Security

Hardware requirements:
•	Arduino UNO
•	Flame sensor
•	GSM module
•	GPS module
•	LED and Buzzer 
•	Breadboard
•	Jumper wires

Software requirements:
•	Arduino IDE

Methodology:

The main principle behind the working of the ‘Fire Detection Alarm’ is Infrared radiation.  The flame sensor uses Ultraviolet (UV) or Infra-Red (IR) technology to identify flames meaning they can alert to flames in less than a second. 
The major component of a flame sensor system is the sensor itself. It comprises of photoelectric detective circuits, signal conditioning circuits, microprocessor systems, I/O circuits. The flame sensor has a VCC(5v) for supply, GND, and Digital output pin (DO).
The next important sensor is Arduino UNO which is programmed as to when ever fire is detected flame sensor will detect that and send alert signals. We have use GSM module which will do alert call and send SMS on given mobile number, GSM has transmitter (TX), receiver (RX), 
and GND pin for transmitting the signal. We have given 12V 2Amp supply to GSM module and inserted a Sim card for cellular connectivity. The next sensor which will collect the location coordination is GPS module it contains an antenna for receiving longitude and latitude 
coordinates of the current location where the fire is detected. It has VCC (3.3v), GND, has transmitter (TX), receiver (RX) pin which are connected to the Arduino as the following circuit diagram. Now alarming devices are buzzer and led which are active when fir is detected.
