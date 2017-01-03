---
title: Test
date: 2016-12-27 03:00:01
tags:
---

## before starting

We will use the [firmata][1] protocol to talk with the microcontroller.

Firmata is a protocol based on midi that provide an "API" to control your MCU hardware.

In the examples and exercices that you will find here, we will use Javascript, nodejs, and the [Johnny-Five][2] package

You will need [nodejs][3] (somehow recent) to use the test tool and the workshoper 

## Test firmata on the board

the board should be flashed with firmata but let's try anyway

in a terminal and in your project directory

```
git clone git@github.com:catbotFactory/yldWorkshop.git
cd yldWorkshop
npm install
npm run firmTest
```

firmTest should say something like ```your board is ready to use !``` and exit.

If not keep calm and go [here][4] 

[1]:https://github.com/firmata/protocol
[2]:https://johnny-five.io
[3]:https://nodejs.org/en/
[4]:/troubleshooting#Firmata
