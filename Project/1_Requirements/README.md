# M2_AirQualityMonitor

## Abstract

So basically this project is useful when you are planning to secure your place from any type of gas leakage.
When the LPG gas is detected by the MQ-6 gas sensor in LPG Gas leakage detector using arduino then the green LED will go on otherwise red LED will glow.
To make this project more interesting and user friendly we attach a 16×2 LCD module to it.
You can see the real time status of the working of the gas sensor in this LCD screen.
You can also check the Blynk smart smoke detector made by us.

## Components Used

### Arduino UNO
The Arduino Uno is an open-source microcontroller board based on the Microchip ATmega328P microcontroller and developed by Arduino.cc. The board is equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards (shields) and other circuits.

![image](https://user-images.githubusercontent.com/98815258/155835356-b06acbdf-dc37-45d5-8b1e-89cf53d1b6cc.png)

### MQ-6 gas sensor
MQ6 Gas Sensor The MQ6 Gas Sensor module is useful for gas leakage detection. They are used in gas leakage detecting equipments in home and industry, are suitable for detecting of LPG, iso-butane, propane, LNG, avoid the noise of alcohol, cooking fumes and cigarette smoke.
![image](https://user-images.githubusercontent.com/98815258/155835373-fb49b38f-970f-448c-8e07-a105c368f0b4.png)

### 16×2 LCD module
In most of the applications that's have only small values to show,uses the LCD.
Most of the commercial meters use this module to represent the data output.
In the toys and developing projects,it is still vastly in use.
In black and white printers,it helps to show the printer settings and status.

![image](https://user-images.githubusercontent.com/98815258/155835485-c6af0eee-2304-4eb5-867e-18c34c06f1a0.png)

### 10K potentiometer
A potentiometer is a three-terminal resistor with a sliding or rotating contact that forms an adjustable voltage divider. If only two terminals are used, one end and the wiper, it acts as a variable resistor or rheostat. The measuring instrument called a potentiometer is essentially a voltage divider used for measuring electric potential (voltage); 

![image](https://user-images.githubusercontent.com/98815258/155835503-41a944bf-e9e8-4cea-8a5d-b17e3a90e22f.png)

### Red and green LEDs
A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons. The color of the light (corresponding to the energy of the photons) is determined by the energy required for electrons to cross the band gap of the semiconductor

![image](https://user-images.githubusercontent.com/98815258/155835525-b68f8a27-936e-4aef-8eb2-79d747ff4795.png)

### 220 ohms resistors
![image](https://user-images.githubusercontent.com/98815258/155835565-f5252122-82a9-42b3-9b29-c2a419b7c9ba.png)

### Wires

wires used to connect components


<br>
<br>
<br>

## High Level Requirements
  
| ID | Description | Status |
|----|-------------|--------|
| HLR01 |detecting gas     | Implemented |
| HLR02 | detecting gas level    | Implemented |
| HLR03 | information to lcd and leds | Implemented |
<br>
<br>
<br>
<br>

## Low Level Requirements
 
| ID | Description | Status |
|----|-------------|--------|
| LLR01 | different colour leds          | Implemented |
| LLR02 |  detecting gas level      | Implemented |

