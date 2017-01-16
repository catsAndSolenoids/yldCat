---
title: Connect
date: 2016-12-28 02:00:01
---

## before starting
let's have a look at our Funduino and explain terms we will be using later

- 1 : USB connector, where you will plug the usb cable to your computer
- 2 : Voltage switch, change boards and pin voltage (3V3 or 5V) (put yours to 5V)
- 3 : Power in, barrel (circular) connector you plug the 9v PSU here
- 4 : D13 led, onboard led, linked to pin 13
- 5 : Signal pins row, 14 contollable pin
- 6 : Vout pins row, 14 pin providing 3V3 or 5V depending on board conf  
- 7 : Ground pins row, 14 pin to the gnd

<div class="funPict">
![img caption](funduino.png)
</div>

Start by unpluging the funduino from usb and / or power before connecting anything.
then check that the voltage switch (2) is set to 5V (servomotors need 5V)

## laser
the laser has 2 wire, from the laser itself the wire are red and blue, they later connect to other colors, we will call the blue one ground and the red on signal.
connect the ground wire to the pin 13 in the ground (7) row (on the 'laser' col in the pict)
then connect the signal wire to pin 13 in the signal (5) row (yellow one)

##  Y axis servo
the Y axis is the servo motor on the top part, linked to the laser.
the servo have a connector at the end of the wire the collored wire are 

- brown : ground wire => blue row
- red : Vin wire => red row
- orange : signal wire => yellow row

place the connector on the D11 col, jumping one col after the laser one.

## X axis servo
Same as Y but on D10 the row befor the X one

Congratulation, your catbot is close to be complete !

## Joystick
if you have a joystick in your kit, it comes with a strip of five wires, connect them to the joystick and link the wire with the pins in the Joystic section of the image

## Next step
if you want to learn to program your catbot go [here][1]

[1]:/test
