<img src="{{ "/pictures/dipduck.jpg" | prepend: site.baseurl }}" />
## Purpose
   This project is a small HID device that can emulate a keyboard and input a large amount of keystrokes in a short amount of time. It can be used to automate work, execute scripts, or capture data.

<br>  A slight modifcation on Seytonic's orginal design. It is a USB Rubber Ducky w/ microSD support and dip switches to select between various scripts.

## BOM
  - Arduino Pro Micro (lenardo - atmega23u4)
  - microSD card reader
  - microSD card
  - otg cable

## Plan
  After testing functionality on a breadboard, I plan to solder the wires on the boards then hotglue them together in a similar fashion as Seytonic.

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

The code can be found on Seytonic's website and I created my own scripts to use with this duck.

<a href="http://mitchellstride.com/">HOME</a>
