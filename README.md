# led-flasher
led-flasher
beee lab. 

Aim:-To make a led flasher using arduino. 

EQUIPMENTS:- bread board,arduino,connecting wires,arduino board,resistor,led bulbs. 


CODE:- void setup()
{

// initialize digital pin 0 as an output.

pinMode(0, OUTPUT);

}


// the loop function runs over and over again forever

void loop()
{
digitalWrite(0, HIGH); // turn the LED on (HIGH is the voltage level)

delay(500); // wait for a second

digitalWrite(0, LOW); // turn the LED off by making the voltage LOW

delay(500); // wait for a second

}

LEARNING OUTCOMES:-1.Learned how to make a LED flasher using breadboard and arduino.

PRECAUTION/ERROR:-1.Connection should be proper. 2.Resistors should not be of high resistance.vv

