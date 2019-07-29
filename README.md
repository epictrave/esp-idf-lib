# ESP-IDF Components library

[![Build Status](https://travis-ci.org/UncleRus/esp-idf-lib.svg?branch=master)](https://travis-ci.org/UncleRus/esp-idf-lib)

Components for Espressif ESP32 [ESP-IDF framework](https://github.com/espressif/esp-idf)

Most of them ported from [esp-open-rtos](https://github.com/SuperHouse/esp-open-rtos).


## Components

| Component      | Description                                                             | License | Thread safety
|----------------|-------------------------------------------------------------------------|---------|---------------
| **i2cdev**     | I2C utilites                                                            | MIT     | Yes
| **ds1302**     | Driver for DS1302 RTC module                                            | BSD     | No
| **ds1307**     | Driver for DS1307 RTC module                                            | BSD     | Yes
| **ds3231**     | Driver for DS3231 high precision RTC module                             | MIT     | Yes
| **hmc5883l**   | Driver for HMC5883L 3-axis digital compass                              | BSD     | Yes
| **qmc5883l**   | Driver for QMC5883L 3-axis magnetic sensor                              | BSD     | Yes
| **onewire**    | Bit-banging one wire driver                                             | MIT*    | No
| **ds18x20**    | Driver for DS18B20/DS18S20 families of one-wire temperature sensor ICs  | BSD     | No
| **dht**        | Driver for DHT11, AM2301 (DHT21, DHT22, AM2302, AM2321), Itead Si7021   | BSD     | No
| **sht31x**     | Driver for Sensirion SHT3x digital temperature and humidity sensor      | BSD     | Yes
| **bmp180**     | Driver for BMP180 digital pressure sensor                               | MIT     | Yes
| **bmp280**     | Driver for BMP280/BME280 digital pressure sensor                        | MIT     | Yes
| **bh1750**     | Driver for BH1750 light sensor                                          | BSD     | Yes
| **ultrasonic** | Driver for ultrasonic range meters, e.g. HC-SR04, HY-SRF05              | BSD     | No
| **pcf8574**    | Driver for PCF8574 remote 8-bit I/O expander for I2C-bus                | MIT     | Yes
| **mcp23008**   | Driver for 8-bit I2C GPIO expander MCP23008                             | BSD     | Yes
| **mcp23017**   | Driver for 16-bit I2C GPIO expander MCP23017                            | BSD     | Yes
| **hd44780**    | Universal driver for HD44780 LCD display                                | BSD     | No
| **pca9685**    | Driver for 16-channel, 12-bit PWM PCA9685                               | BSD     | Yes
| **ms5611**     | Driver for barometic pressure sensor MS5611-01BA03                      | BSD     | Yes
| **ads111x**    | Driver for ADS1113/ADS1114/ADS1115 I2C ADC                              | BSD     | Yes
| **pcf8591**    | Driver for 8-bit ADC and an 8-bit DAC PCF8591                           | BSD     | Yes
| **tsl2561**    | Driver for light-to-digital converter TSL2561                           | BSD     | Yes
| **tsl4531**    | Driver for digital ambient light sensor TSL4531                         | BSD     | Yes
| **max7219**    | Driver for 8-Digit LED display drivers, MAX7219/MAX7221                 | BSD     | Yes
| **tda74xx**    | Driver for TDA7439/TDA7439DS/TDA7440D audioprocessors                   | MIT     | Yes
| **mcp4725**    | Driver for 12-bit DAC MCP4725                                           | BSD     | Yes
| **encoder**    | HW timer-based driver for incremental rotary encoders                   | BSD     | Yes
| **ina3221**    | Driver for INA3221 shunt and bus voltage monitor                        | MIT     | Yes
