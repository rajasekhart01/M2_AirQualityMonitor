# M2_DistanceMeasuringDevice

## Abstract
Atmega 328 micro controller is combined with ultra sonic sensor to detect the distance been travelled by the object. where we have inserted the lcd display acts as digital actuator and tells us the measurement which was captured by sensor and processed by AU. this devicing system is useful to detect the depths, height, horizontal distance. if we inegrate the project it will be useful for automotives, machinaries etc,. 
## Components Used

### ATmega328
The ATmega328 is a single- chip microcontroller created by Atmel in the megaAVR family (later Microchip Technology acquired Atmel in 2016). It has a modified Harvard architecture 8-bit RISC processor core.so 8-bit, 28-Pin AVR Microcontroller follows RISC Architecture and has a flash-type program memory of 32KB

![image](https://user-images.githubusercontent.com/98815258/157280219-9148c462-9d73-4afc-a3ec-27cf657ee882.png)


### HC-SR04 sensor
  A sound sensor is defined as a module that detects sound waves through its intensity and converting it to electrical signals.
![image](https://user-images.githubusercontent.com/98815258/157276577-bed08f5d-1477-4f5c-9972-04cdd7276999.png)


### 16×2 LCD module

In most of the applications that's have only small values to show,uses the LCD.
Most of the commercial meters use this module to represent the data output.
In the toys and developing projects,it is still vastly in use.
In black and white printers,it helps to show the printer settings and status.

![image](https://user-images.githubusercontent.com/98815258/155835485-c6af0eee-2304-4eb5-867e-18c34c06f1a0.png)

### 1K Potentiometer
A potentiometer is a three-terminal resistor with a sliding or rotating contact that forms an adjustable voltage divider. If only two terminals are used, one end and the wiper, it acts as a variable resistor or rheostat. The measuring instrument called a potentiometer is essentially a voltage divider used for measuring electric potential (voltage); 

![image](https://user-images.githubusercontent.com/98815258/155835503-41a944bf-e9e8-4cea-8a5d-b17e3a90e22f.png)

### Wires

wires used to connect components


<br>

## High Level Requirements
  
| ID | Description | Status |
|----|-------------|--------|
| HLR01 | Measuring the ditsance  Moved  | Implemented |
| HLR02 | detecting obstacles    | Implemented |
| HLR03 | displaying the Information  | Implemented |
<br>

## Low Level Requirements
 
| ID | Description | Status |
|----|-------------|--------|
| LLR01 | Measuring in particular units         | Implemented |
| LLR02 |  Displaying real-time    | Implemented |

## 4Ws & 1H
### What:
Distance is a numerical measurement of how far apart objects or points are.Ultrasonic sensor provides an easy way in distance measurement.
### Why:
Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications.
### When:
The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display.
### Where:
Measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems.
### How:
This project, we have used the HC-SR04 Ultrasonic Sensor with ATMEGA328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO.
