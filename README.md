The project is to implement an Arduino microprocessor to control the functions of a pre-built RC car.

The primary objective of this project was to make the car function using a Android device. To implement

the functionality and use the Android device with Bluetooth, we would use an open-source “software.h”

library. With the use of this library, we are able to use the bluetooth controller to connect between the

android device and the Arduino microprocessor. Once the connection is complete, we will be able to

use Android device to perform functions such as moving the car forwards, backwards, left and right.

#Requirement and Material

- Important libraries that are required
You will need to use a library softwareserial.h. The detailed information regarding the content of the library can be found on the link below.
Softwareserial.h -https://www.arduino.cc/en/Reference/SoftwareSerial

This library is already intalled on auridino so we do not need to install it.To use thislibrary we have to include < Softwareserial.h > in your code.

###List of Material:

RC Car from Walmart.  (It cost $30 at my local Walmart.)

Arduino microprocessor

HC -06 bluetooth module

HBridge Ld293d

25 wires, 8 jumper wires

2 DC motors

9V Battery

Battery Wires , USB cable compatible with aduino

Screwdriver

Wire Stripper

Friends to bring you food when u get tired

A device to send instructions to your bluetooth module

A device to recive instructions to your bluetooth module

###Build instructions :

Building the Rc car is easy and simple
unnamed

schematics of rc car schematics of rc car 2 jpeg This Reposity Consit of Following things:

Source code - It includes the final code You wil need to upload to your auridino

Bluetoothrccar- picture of hc-06 used in the project

libraries - Libraries that were used

images - the folowing image files are there - Schematics, whole circuit picture, bluetooth rc car, Hbridge

LICENSE - The license file.

README.md - The file you're reading now! :-D

Usage
Using the Rc car is very easy , whem You make the crcuit as shown abhove and install the code

You will have to install an app smart bluetooth on your android device and connect to bluetooth named ITEAD when you are connected, it will give you an option to send istructions.

0- will make the car go forward.
1- will make the car g reverse .
b- will stop the car .
l- will make the car go left.
r- will make the car go right.
s- will make go straight again.

###Team Chashamnoor Singh
