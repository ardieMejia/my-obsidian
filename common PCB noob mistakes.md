
According to this one [good video on beginners mistakes](https://m.youtube.com/watch?v=hkSad4n76Lc), the first is temptation to make your own etching,  since it's a rather hacky process.  This is prone to messes.

When designing your first PCB from scratch, expect it to fail.  Design it large becoz PCB manufacturers charge 100m2 for only a few dollars.  Don't aim for enclosure fitting. 

Design a PCB without a test point. Place test pads. 

No power or diagnostic LEDs. Something simple like 5 volts indicator can save hours of headache

Overcrowd circuits.  Only decoupling Caps should be close.

Not taking advantage of the Silkscreen. Use markings for each component.  With a dot or line to mark pin 1. To indicate orientation of component.  Text should be 2mm.

Don't forget to use isolation jumpers 

Not breaking out unused GPIOs. Most projects don't use all GPIOs. Break out a few to test pads. Rerouting extra GPIOs only takes a few seconds. 

UART mixups. Its easy to confuse transmit and receive.  

I2C addressing confusion. [[I2c addressing]] is an important part of dealing with I2c communication. 