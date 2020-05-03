__Ideation of the project 'Electronic juice vending machine'__

The web link of the project description: [Electronic juice vending machine](https://nevonprojects.com/android-powered-juice-vending-machine/)

__Problem statement:__ To have an automatic juice vending machine which pours the juice if a coin is inserted. Also, it must provide options for the user and must detect the presence of a glass on its own.

__Ideation phase:__ The basic mechanism is:

Coin module and bluetooth module => Microcontroller => Glass detector module => Microcontroller => Motor module

In the suggested project, the components used are:

ATMEGA328P microcontroller

Bluetooth module for wireless communication

IR sensors for glass detection

| Component | Feasibility | Advantages | Disadvantages |
|-----------|-------------|------------|---------------|
|Microcontroller|Quite easy if familiar with its basics| Our solution could be even more versatile if we can hack on the microcontroller|Usually tough to start with since they are PLDs basically and demand some programming skills beforehand|
|Wireless communication module|Tough to start with and demand some dedicated components|Learning outcomes are high|Require some money as components may be costly|
|Glass detection| One of the easiest modules to hack on with| Cost can be significantly reduced|Precision in measuring the glass distance may be lost to some extent|

The suggested approach is really good. It also has bluetooth module for wireless control. But, I personally feel pushbuttons would do the job. Since, in this case the users are going to be near the vending machine, simple pushbuttons can be used instead of bluetooth for flavor and quantity selection. Also, instead of IR sensors, LED-LDR combination can be used to detect the glass. This is because, in this case the distance of the glass from the sensor doesn't matter. Only its presence matters. Hence, having an LED-LDR combination and the glass slot in between would enable its detection. In this way, the cost can be significantly reduced.

