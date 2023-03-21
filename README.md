# Ostrich

![Ostrich](https://i.imgur.com/nRR0zSH.jpg)

34 key keyboard based on RP2040 with canted MCU.

This keyboard was inspired by the Reviung34 keyboard.

You can find the qmk firmware [here](https://github.com/doesntfazer/Keyboard-Dweebs-Firmware-repository/tree/main/QMK/ostrich)

  
If you are interested in using VIAL instead, (This is a GUI for qmk). Then please go [here](https://github.com/doesntfazer/Keyboard-Dweebs-Firmware-repository/tree/main/VIAL-QMK/ostrich)

It is important to note, the 0.9 version of this keyboard keyboard is built with an mcp23017-e/so MCP chip instead of using diodes.  
This chip requires pull-up resistors. Since this was meant to use an OLED, it just borrows the one built into the SSD1306. If you decide you don't want an OLED, you will need to solder pull up resistors on GP0 and GP1. (4.7k have been sufficient in my testing)

If you are using the 1.0 or later versions of this keyboard, the keyboards will use diodes, and you won't have to worry about it.
