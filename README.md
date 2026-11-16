## Adafruit MCP2222 Breakout - General Purpose USB to GPIO/SPI/I2C - Stemma QT / Qwiic PCB

<a href="http://www.adafruit.com/products/6559"><img src="assets/6559.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit MCP2222 Breakout - General Purpose USB to GPIO/SPI/I2C - Stemma QT / Qwiic. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/6559

### Description

Wouldn't it be cool to drive a [tiny OLED display](https://www.adafruit.com/categories/98), read a [color sensor](https://www.adafruit.com/product/6461), or even just flash some LEDs directly from your computer?  Sure you can program an [Arduino](https://www.adafruit.com/products/50) or [QT Py](https://www.adafruit.com/search?q=qt+py) to talk to these devices and your computer, but why can't your computer just talk to those devices and sensors itself?  Well, now your computer *can* talk to devices using the Adafruit MCP2222 breakout board\!

What can the MCP2222 chip do?  This chip from [Microchip](https://www.microchip.com/en-us/product/mcp2222) is similar to a USB to serial converter chips but adds a GPIO, UART Serial, SPI and I2C interface as well. The I2C interface is great for talking to OLEDs, sensors, PWM drivers, its the most popular interface for small devices. SPI is for more sensors and many TFT displays. You can use the GPIO to do things like flash LEDs, read switches or buttons, and more. The MCP2222 breakout is like adding a little multi-tool for serial protocols to your computer\!

One nifty capability of the MCP2222, unlike most USB-to-GPIO converters is the ability to use 3.3V *or* 5V logic. This makes it good for interfacing with some older sensors and devices that want 5V signals.

Please note: The MCP2222 has more GPIO than the MCP2221, and comes with SPI too. But it does not have ADC or DAC like the '2221. Also, the SPI has inter-byte gaps so it cannot be used for 'fake' NeoPixel writes by modulating the MOSI pin.

This chip is powerful and useful to have when you want to use Python (for example) to quickly iterate and test a device that uses SPI, UART, I2C or general purpose digital  I/O. There's no firmware to deal with, so you don't have to deal with how to "send data to and from an Arduino which is then sent to and from" an electronic sensor or display or part.

This breakout has an MCP2222 chip, USB C connector, on-board 3V regulator, and a 4 pin JST SH port for I2C connectivity with 3V or 5V power and logic. [This port is Stemma QT / Qwiic compatible](https://adafruit.com/stemma) for use with any sensor or chip that that has a matching port \- you can even wire in Grove I2C devices with an adapter cable with no soldering required\! [See this guide for more info on Stemma QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt)

[Check out all our Stemma QT sensors, cables, and devices you can use here.](http://adafruit.com/stemma)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
