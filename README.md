# MUSIC-USING-CANS
This project involves making a launch pad using MPR121 through laptop and then serial communicating with a microcontroller(Arduino UNO) to produce sound when the can is touched.

## How it Works?  

  First of all, the 12 electrode of the MPR121 sensor are connected to the cans.
  
  MPR121 Breakout → Arduino Uno
  
	3.3V → 3.3V
  
	SCL → A5
  
	SDA → A4
  
	GND → GND
  
	IRQ → D2
  
	Now with the help of PySerial , communication between  arduino and Windows takes place.
  
	Now if we touch the cans , tune respective to each can is made.


### Components Used 

	Arduino UNO
  
	MPR121

### Language and Libraries

Python and C 

	MPR121

	wire.h 

	Winsound 

	Pyserial 
  
  
  
