Consider a scenario where you have an MCU with one pin configured as an input. If a program reads this input, will it be high (VCC) or low (ground)? The answer is we don't know, and this is where pull up and pull down resistors are used. Pull ups are more common.  

This can be confusing for beginners,  but have a look at the first diagram [here](https://learn.sparkfun.com/tutorials/pull-up-resistors/all),  and imagine the circuit without the resistors,  and how tricky it is to get the same behaviour. The examples are almost always the same in other sites like in [this article](https://www.build-electronic-circuits.com/pull-up-resistor/),  which means this is common usage. 

It is so common, that many MCUs have internal pull ups. An example is the ATmega328 microcontroller on Arduino