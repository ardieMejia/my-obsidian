I2c can have hard code address or configurable address. Configurable address can have more than 1 pins. 

Configurable addresses can result from pulling a pin high or low. In this case, a [[pull up and pull down resistor]] is used.

When 2 devices share the same address, a selecting mechanism is required, such as powering down a device.  An i2c multiplexer also works,  but this means buying another component. 