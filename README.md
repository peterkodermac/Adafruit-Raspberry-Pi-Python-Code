# Raspberry Weather DHT22 

## Introduction

This code helps you read temperatures along with humidity and save both in your database. You need to configure your weather station in order to use this code. Read more on www.raspberryweather.com.

The PressureWind branch (http://goo.gl/JXv3Ht) created by A. Catorcini is an expansion to the basic functionalities. Take a look if you want to display wind speed and barometric pressure!

## Installation

First, you need to install the DHT22 library by Adafruit and some additional software:

> git clone https://github.com/adafruit/Adafruit_Python_DHT.git

> cd Adafruit_Python_DHT

> sudo apt-get update

> sudo apt-get install build-essential python-dev python-openssl

> sudo python setup.py install

If everything is wired correctly, test the setup with
> sudo ./AdafruitDHT.py 22 4

Where 22 is the DHT22 sensor and 4 represents pin #4
