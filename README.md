# PIR_SKETCH
This sketch reads data from a PIR sensor, lights an LED and writes to Arduino IDE's Serial Monitor when motion is detected.

In order for this to work, follow these steps:
1. connect the PIR wires to a breadboard 
2. connect jumper wire on breadboard parallel to gnd wire from PIR, connect other end to gnd on arduino
3. connect jumper wire parallel to "out" from arduino on breadboard and to pin 8 on arduino
4. connect jumper wire parallel to +5v from arduino on breadboard to 5v on arduino
5. connect led negative side parallel to gnd on breadboard, positive not parallel to anything
6. connect wire not parallel to anything on breadboard and in pin 3 on arduino
7. connect 220 ohm resistor parallel to positive led and parallel to wire connected to pin 3
8. download arduino IDE
9. create a sketch
10. paste code
11. upload sketch
12. open serial monitor (top right icon in IDE)
