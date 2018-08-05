ARDUINO_DIR   = /Applications/Arduino.app/Contents/Java
ARDUINO_PACKAGE_DIR = $(HOME)/Library/Arduino15/packages
ALTERNATE_CORE_PATH = $(HOME)/Library/Arduino15/packages/adafruit/hardware/samd/1.2.1
CMSIS_DIR = $(ARDUINO_PACKAGE_DIR)/arduino/tools/CMSIS/4.5.0/CMSIS
CMSIS_ATMEL_DIR = $(ARDUINO_PACKAGE_DIR)/arduino/tools/CMSIS-Atmel/1.2.0/CMSIS
ARCHITECTURE = sam
BOARD_TAG     = adafruit_feather_m0
CXXFLAGS_STD = -DARDUINO_ARCH_SAMD
ARDUINO_OTA = $(ARDUINO_PACKAGE_DIR)/arduino/tools/arduinoOTA/1.2.0/

ARDUINO_LIBS += Wire SPI PWFusion_AS3935_I2C

include /usr/local/opt/arduino-mk/Sam.mk

#CC = arm-none-eabi-g++
CXX = arm-none-eabi-g++
