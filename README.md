## Adafruit DC Power BFF Add-On for QT Py PCB

<a href="http://www.adafruit.com/products/5882"><img src="assets/5882.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit DC Power BFF Add-On for QT Py. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5882

### Description

We were recently working on a project where we really wanted to power a QT Py ESP32 from 12V - but the only power input on the board is basically USB 5V max. Never one to give up, we designed an add-on that will allow anyone to use a QT Py or Xiao dev board with up to 20V DC power!

In the center is an MPM3610 integrated buck converter, which will generate 5V from up to 20V input, with cool DC/DC technology so there's no heat-sink needed. The MPM3610 can give about 1 Amp output, which should be plenty even if you have LEDs, WiFi connectivity, displays or even a small motor or servo.

The board features both 3.5mm terminal block and 2.1mm DC jack inputs, protected with a Schottky diode. You can use either to power the board, but don't plug in different power inputs to both - they're wired directly together on the BFF. If you're using the DC jack to power, you can use the terminal block as an 'pass through output' to connect other high-voltage devices.

There's two small enable and an ground solderable pads next to the terminal block so you can use an external switch to disable the converter. 

Since its a bulky add-on with through hole components, compared to most of our other BFF boards, we think it's best to use socket header to plug a QT Py on top, rather than trying to have it solder back-to-back. For that reason we include two 7-pin socket headers. Solder them so that the QT Py sits on the top, there's two break-apart railings that can be used to bolt the board since plugging in a jack requires  mechanical stabilization.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
