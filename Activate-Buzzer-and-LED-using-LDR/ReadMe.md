Hi everyone, this is a quick and simple tutorial on how to activate a Buzzer and LED using Arduino UNO and LDR.



Required Hardware:



1- Arduino Board

2- Buzzer

3- LED

4- LDR

5- 220 and 10K ohm Resistor

6- Jumper Wires

7- Breadboard


So first thing to do is to connect all the LED, LDR, and Buzzer to the Breadboard. Then, we attach a 10K ohm resistor to the board from one of the leg of the LDR. Next, we attach a 220 ohm resistor to the board from LED long leg(anode). After that, we connect all the ground from the LDR, Buzzer, LDR under one ground and then connected it to the pin GND(POWER INPUT) on the Arduino board using jumper wire. Then, we plug in a jumper wire to pin +5V(POWER INPUT) from the arduino to the LDR remaining leg. We use again a new jumper wire connected to Buzzer long leg(positive)from Digital pin 12. Lastly, we connected to the remaining leg of 220 ohm resistor a jumper wire from Digital pin 13.


Down here are the schematic diagram of the circuit from the TinkerCAD project:

https://www.tinkercad.com/things/4eg2UnfDHQY-brilliant-snaget/editel?tenant=circuits



This is a very simple project that anyone can make, using only a few components to achieve the goal

It is also good to understand how Arduino outputs works and also the For loop.

Thanks for passing by....
