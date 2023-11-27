# RC-car-parktronic
A remote control car(Bluetooth) that when parking, has to stop itself from crashing at the objects behind her, plus we will add some features later on for once this is done

**Hardware preparation**

Materials you'll need:

Arduino Uno board.
Bluetooth module.
USB cables for the Arduino.
Jumper wires (optional, depending on your setup).
Steps:

Connect the Arduino to the PC

a. Connect one Arduino Uno to your computer via a USB cable.

b. Connect the Bluetooth module to your arduino, I am personally using digital pinds 2 and 3 because there's a problem when I put them on 0 and 1

Identify the Hardware UART Pins:

And we will be transmitting commands from the bluetooth sender(in this case it's your phone) to the receiver's(arduno's) serial. 
