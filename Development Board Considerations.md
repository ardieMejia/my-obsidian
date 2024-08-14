
Considerations when choosing development board:
1. Programming lang and OS of choice
	- C, C++ are universal, and Arduino (and some  others)  sport custom IDEs  with libraries, many microcontroller boards also use Arduino's IDE
	- BeagleBone Black lets you use Android
2. Specs
	- CPU clock speed,  its  okay choose normal
	- Memory RAM, more maybe worth it, especially if your project needs it
	- GPU, if your project involves gaming/facial   recognition. This isnt really a bad idea. 
	- storage space
	- analog pins, for  reading data from  analog  sources, often connected to an ADC (Analog to Digital Converter) inside, each board has a resolution spec, so for example, Arduino's ADC is  1024, so  reading a 5V --> 5v/1024 reads 5mV smallest unit.
	- PWM, pulse width modulation, useful  for  driving a servo for example.  Also, like the analog  pins, has resolution and sampling rate
	- Power consumption, often overlooked, some boards have a low-power mode, it goes to  sleep when not in use. 
	- Price, can range from 5 dollars to 270 dollars. FPGA boards can range from 95 dollars to 195 dollars. These are really cool and are worth exploring. 