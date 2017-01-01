---
title: troubleshooting
date: 2016-12-25 00:10:44
tags:
---

here we will talk about the possible problem you may encounter

## Firmata
to install firmata on your  board, you can use [firmata-party][1]
plug the arduino to your computer

```
npm install -g firmata-party
firmata-party uno
```
DONE

you can also use the arduino IDE 

- [Download arduino IDE][2]
- Plug the arduino in a usb port
- Open the arduino IDE. Ensure that you selected your arduino type (arduino uno)and port
- Open Files > Examples > Firmata > StandardFirmata
- Upload it (the button with an arrow in the IDE or File > Upload).


[1]: https://github.com/noopkat/firmata-party
[2]: https://www.arduino.cc/en/Main/Software
