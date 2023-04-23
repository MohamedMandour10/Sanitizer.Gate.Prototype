
# Optics based Sensitizer Gate model
This project is an implementation of an optics-based model for a sensitizer gate. The project uses the following components:

* Arduino board
* Buzzer
* LDR (Light Dependent Resistor)
* Light source (such as an LED or lazer)
* Servo motor
* Mirrors

## Description
The model is based on the principle of the Optics-based Sensitizer Gate, which uses light to control the flow of fluid or gas. The gate is composed of a transparent channel and two photosensitive elements. When light is shone on one of the photosensitive elements, it causes a reaction that alters the properties of the gate and allows fluid or gas to flow through. The Optics-based Sensitizer Gate has applications in fields such as microfluidics, microreactors, and microvalves.

The project aims to demonstrate the principle of the Optics-based Sensitizer Gate using a simplified model. The model consists of a  light source (a lazer), four mirrors to direct the light to the photosensitive elements, an LDR to detect the light, a buzzer to indicate the flow of fluid or gas, and a servo motor to control the gate.

## Functionality
The model works as follows:

The light source is turned on.
The light is directed towards one of the photosensitive elements using a mirror.
The LDR detects the change in light intensity caused by the reaction in the photosensitive element.
The buzzer is turned on to indicate the flow of fluid or gas.
The servo motor is activated to control the gate.
Repository Contents
The repository contains the following files:

* README.md: this file
* code.ino: the code to run on the Arduino board
* schematic.png: the schematic of the model
* report: full details about the prototype
* circuit diagram

## Circuit diagram
![circuit diagram](https://ibb.co/6th75wV)

## Usage
To use the model, follow these steps:

Connect the components as shown in the schematic.
Upload the code to the Arduino board.
Power the Arduino board.
The model should now be running.

