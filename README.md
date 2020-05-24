# Raspberry-Pi-Projects

### MAX30102 / MAX30105 Pulse Oximeter and Heart-Rate Sensor

#### vrano714 tutorial
 - at Qiita https://qiita.com/vrn/items/1ac58c61194b23af1d8c by vrn
 - https://github.com/Naohiro2g/max30102-tutorial-raspberrypi  by vrano714
 - https://github.com/Naohiro2g/max30102  by doug-burrell, no interrupt, polling version

#### mfitzp
 - https://github.com/Naohiro2g/max30100  by mfitzp
 - https://github.com/Naohiro2g/MAX30102-in-raspberry-pi-

#### Pimoroni Breakout Garden
 - https://github.com/Naohiro2g/max30105-python by pimoroni
 - Breakout Garden HAT https://shop.pimoroni.com/products/breakout-garden-hat
 - MAX30105 https://shop.pimoroni.com/products/max30105-breakout-heart-rate-oximeter-smoke-sensor
 - from Sparkfun Sensor Library Example5_HeartRate https://github.com/Naohiro2g/SparkFun_MAX3010x_Sensor_Library


### VL53L1X ToF LASER Ranging Sensor, or LIDAR 
 - https://github.com/Naohiro2g/vl53l1x-python
 - https://github.com/Naohiro2g/vl53l1xToWebSocket/

### MPU6050 Six-Axis (Gyro + Accelerometer) MEMS MotionTracking Device
- teapot on RasPi, server/client
   - https://github.com/Naohiro2g/MPU6050_teapot_demo
- teapot with DMP
   - https://github.com/Naohiro2g/PiBits
- with complementary filter
   - https://github.com/Naohiro2g/MPU6050_Demo_on_Raspberry-Pi

Using complementary filter. 
 - http://blog.bitify.co.uk/2013/11/using-complementary-filter-to-combine.html
 - http://blog.bitify.co.uk/2013/11/reading-data-from-mpu-6050-on-raspberry.html

for Sunfounder kit with drift parameters
 - http://wiki.sunfounder.cc/index.php?title=MPU6050_Module

Information at www.i2cdevlib.com
 - [MPU6050 Class Reference](https://www.i2cdevlib.com/docs/html/class_m_p_u6050.html)
 - [MPU6050 Register Map](https://www.i2cdevlib.com/devices/mpu6050#registers)

fork from jeff rowberg
 - [Raspberry Pi](https://github.com/Naohiro2g/i2cdevlib/tree/master/RaspberryPi_bcm2835)

### BME280 Pressure, humidity and temperature Sensor

- https://github.com/Naohiro2g/bme280
- https://github.com/Naohiro2g/Adafruit_Python_BME280

### PWM Controller for LED/Servo [PCA9685]
- https://github.com/Naohiro2g/Adafruit_Python_PCA9685
- https://github.com/Naohiro2g/micropython-adafruit-pca9685

### IPS LCD [ST7789, SPI/I2C] (ST7789 is very similar to ST7735)
- https://github.com/Naohiro2g/Python_ST7789
- 1.3 inch 240x240 SPI/I2C IPS LCD without CS from Ali Express
- (https://github.com/Naohiro2g/st7789mpy) MicroPython

### IPS LCD [ST7789, SPI/I2C] Gerber data for breakout board
### how to use it as the main screen of Pi
- https://github.com/Naohiro2g/ST7789_1.3_screen
- https://facelesstech.wordpress.com/2019/01/27/1-3-screen-with-raspberry-pi/
- https://www.waveshare.com/1.3inch-lcd-hat.htm
- 1.3 inch 240x240 SPI/I2C IPS LCD Module with MicroSD and Joystick from waveshare

### luma.oled and luma.examples [SSD1306, SPI/I2C]
- https://github.com/Naohiro2g/luma.oled
- https://github.com/Naohiro2g/luma.examples
- Python library for Raspberry Pi and SDD1306 Display Driver connected via I2C/SPI
- OLED 128 x 64 Display and 8x8 pixel Japanese font misakifont

### luma.led_matrix [MAX7219]
 - https://github.com/Naohiro2g/luma.led_matrix/blob/master/doc/install.rst
 - https://github.com/Naohiro2g/luma.led_matrix
 - MAX7219 Dot Matrix Driver via SPI, 8x8 dot matrix LED
 - WS2812 RGB NeoPixels
 
### RGB NeoPixels 8-dot strip [WS2812]
https://github.com/Naohiro2g/rpi-ws281x-python
https://github.com/Naohiro2g/luma.led_matrix/blob/master/doc/install.rst
 - WS2812 RGB NeoPixels (5/3.3V, GPIO18/12, GND)

### 4-digit 7-segment LED Display [TM1637, not I2C]
- https://github.com/Naohiro2g/tm1637-pi-python
- (https://github.com/Naohiro2g/tm1637)
- (https://github.com/Naohiro2g/raspberrypi-python-tm1637)
- TM1637 LED Driver for 8-segment by 6 digits via I2C-like 2-wire, not I2C

### GPIO Zero Recipes [LED, Push Button, Servo, Supersonic Distance]
- https://github.com/Naohiro2g/gpiozero-recipes

### Scratch GPIO Recipes [LED, Push Button, Servo, Supersonic Distance, CdS Light]
- https://github.com/Naohiro2g/scratch-gpio-recipes
- Scratch sample projects using GPIO
- Some wtih ScratchClient https://github.com/Naohiro2g/scratchClient

### Galuca (fork)
- https://github.com/Naohiro2g/Galuca
- Gaxian in Python2/Pygame
- Bug fixed to run on Raspberry Pi or Raspberry Pi Desktop on PC/Mac

### Getting Started with Micecraft Pi translation
- https://github.com/Naohiro2g/getting-started-with-minecraft-pi
- Making Japanese edition by Code2Create.Club

### RGB Controller (fork) [full color LED]
- https://github.com/Naohiro2g/RGBcontroller
- Forked from https://github.com/ebbesmoeller/RGBcontroller (Simple program using Python and module gpiozero to host a webinterface with a color wheel, controlling the color of a RGB led connected to GPIO on a RaspPi.)
- Going to add Color Correction mode.

### RGD Color Sensor [TCS34725 I2C]
- https://github.com/adafruit/Adafruit_Python_TCS34725
- https://github.com/adafruit/Adafruit_CircuitPython_TCS34725
- https://learn.adafruit.com/adafruit-color-sensors/python-circuitpython
- http://www.neko.ne.jp/~freewing/raspberry_pi/raspberry_pi_3_i2c_tcs34725_rgb_color_sensor/

- https://teratail.com/questions/102951
- https://teratail.com/questions/102489

