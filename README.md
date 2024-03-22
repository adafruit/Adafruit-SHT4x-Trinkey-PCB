## Adafruit SHT4x Trinkey - USB Temperature and Humidity Sensor PCB

<a href="http://www.adafruit.com/products/5896"><img src="assets/5896.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a><br>
<a href="http://www.adafruit.com/products/5912"><img src="assets/5912.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit SHT4x Trinkey - USB Temperature and Humidity Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5896
* https://www.adafruit.com/product/5912

### Description

It's half USB Key, half temperature-humidity sensor... it's the Adafruit SHT4x Trinkey. We wanted to make it super-easy to add one of our most popular combination environmental sensors to any computer with a USB A port.

The PCB is designed to slip into any USB A port on a computer or laptop. There's an ATSAMD21 microcontroller on board with just enough circuitry to keep it happy. One pin of the microcontroller connects to a NeoPixel LED. Another pin is used as a capacitive touch input on the end. A reset button lets you enter bootloader mode if necessary. That's it!

The SAMD21 can run CircuitPython or Arduino very nicely - both have existing SHT4x, NeoPixel, and our FreeTouch (capacitive touch) libraries. Over the USB connection, you can have serial, MIDI, or HID connectivity.

There are two versions of this Trinkey: the SHT45 and the SHT41. Sensirion Temperature/Humidity sensors are some of the finest and highest-accuracy devices you can get. The SHT45 sensor is the fourth generation (started at the SHT10 and worked its way up to the top!). The SHT45 has an excellent ±1.0% typical relative humidity accuracy from 25 to 75% and ±0.1°C typical accuracy from 0 to 75 °C. Note that the reported temperature may be a few degrees higher than ambient due to self-heating.

The SHT41 sensor is the fourth generation of I2C temperature and humidity sensor from Sensirion. (They started at the SHT10 and reached the top!). The SHT41 has an excellent ±1.8% typical relative humidity accuracy from 25 to 75% and ±0.2 °C typical accuracy from 0 to 75 °C. Note that the reported temperature may be a few degrees higher than ambient due to self-heating.

The SHT4x Trinkey is perfect for simple projects that want to read the ambient temperature and humidity without extra wiring, soldering, drivers, or complex software. We even ship the board pre-programmed with code that will print a unique serial number, the temperature, humidity, and touch sensor over a serial/COM port in CSV (comma separated value) format, so you can use it immediately.  If you need to measure farther than the computer port, simply use any USB A extension cable.

We think it's just an adorable little board. It's small, durable, and inexpensive enough that it could be a first microcontroller board or inspiration for advanced developers to make something simple and fun.

* ATSAMD21E18 32-bit Cortex M0+ - 48 MHz 32 bit processor with 256KB Flash and 32 KB RAM
* Native USB supported by every OS - can be used in Arduino or CircuitPython as USB serial console, MIDI, Keyboard/Mouse HID, even a little disk drive for storing Python scripts.
* Can be used with Arduino IDE or CircuitPython
* One RGB NeoPixel LED
* One Capacitive Touchpad
* SHT4x Temperature + Humidity sensor with thermal-isolation cutout
* Reset switch for starting your project code over or entering bootloader mode
* Slim and cute, keychain-friendly!

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
