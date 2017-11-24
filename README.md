<img src="{{ "/pictures/dipduck.jpg" | prepend: site.baseurl }}" />
## Purpose
   This project is a small HID device that can emulate a keyboard and input a large amount of keystrokes in a short amount of time. It can be used to automate work, execute scripts, or capture data.
<br>  A slight modifcation on Seytonic's orginal design. It is a USB Rubber Ducky w/ microSD support and dip switches to select between various scripts.

## BOM
  - Arduino Pro Micro (lenardo - atmega32u4)
  - microSD card reader
  - microSD card
  - otg cable

## Plan
  After testing functionality on a breadboard, I soldered the wires to connect the boards and then hotglued them together to create a small solid form factor.

## Wiring

Pro Micro     | microSD
------------- | -------------
Vcc | Vcc
GND  | GND
15  | SCK
14  | MISO
16  | MOSI
4    | CS


  This is the general layout even though the pro micro board is a bit different.


<img src="{{ "/pictures/fritzing.png" | prepend: site.baseurl }}" />


This was the end result.


<img src="{{ "/pictures/dipduck2.jpeg" | prepend: site.baseurl }}" />

## Code & Scripts

<<<<<<< HEAD
The code can be found on my github. It takes Duck Scripts and transfers them into the appropriate actions for the computer. I have used this to automate network configurations at work.
=======
The code can be found on Seytonic's website and I created my own scripts to use with this duck.

<a href="http://mitchellstride.com/">HOME</a>
>>>>>>> 9973435a9b2e7cccaac90ba8f30f146cfb6f5374
