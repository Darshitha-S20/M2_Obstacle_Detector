# Introduction 

An Obstacle detection is the process of using sensors to detect objects or terrain types that impede motion. It basically, measures the distance from the detector to the object or obstacle. In this project, Ultrasonic sensor is used to find the distance measurement of the object. The Ultrasounic sensor uses a technique called “ECHO” which is something you get when sound reflects back after striking with a surface. The sound vibrations can not penetrate through solids. So what happens is, when a source of sound generates vibrations they travel through air, These vibrations when they meet our ear we describe them as sound. As said earlier these vibrations can not go through solid, so when they strike with a surface like wall, they are reflected back at the same speed to the source, which is called echo. Ultrasonic sensor “HC-SR04” provides an output signal proportional to distance based on the echo. The sensor here generates a sound vibration in ultrasonic range upon giving a trigger, after that it waits for the sound vibration to return. Based on the parameters, sound speed and time taken for the echo to reach the source, it provides output pulse proportional to distance. Using this method the obstacle or the object is detected. In this project, HC-SR04 Ultrasounic sensor, ATMEGA328 microcontroller, LCD Display, I2C bus is used for measuring the distance of the object.


# Research 

Ultrasonic sensors work by sending out a sound wave at a frequency above the range of human hearing. The transducer of the sensor acts as a microphone to receive and send the ultrasonic sound. Ultrasonic sensors, like many others, use a single transducer to send a pulse and to receive the echo.  The sensor determines the distance to a target by measuring time lapses between the sending and receiving of the ultrasonic pulse. The working principle of this module is quite simple. It sends an ultrasonic pulse  which travels through the air and if there is an obstacle or object, it will bounce back to the sensor.  By calculating the travel time and the speed of sound, the distance can be calculated. This way it detects the obstacle.


# Features and Components


* ATmega 328-2: This is the microcontroller used in this project. It has 8-bit with a maximum clock frequency of 20MHz, 32KB program FLASH, and 2KB of RAM.
* HC-SR04: This is the ultrasonic sensor which is used in this project. This economical sensor provides 2cm to 400cm of non-contact measurement functionality with a    ranging accuracy that can reach up to 3mm. Each HC-SR04 module includes an ultrasonic transmitter, a receiver and a control circuit. Its operating voltage is 5V.
* I2C to parallel :This is the I2C is a serial communication protocol, so data is transferred bit by bit along a single wire (the SDA line).I2C is synchronous, so the output of bits is synchronized to the sampling of bits by a clock signal shared between the master and the slave. The clock signal is always controlled by the master.
* Hd44780-4 : This is the 16*2 display. The 16×2 translates o a display 16 characters per line in 2 such lines. In this LCD each character is displayed in a 5×7 pixel matrix. 
* BJT : This is the bipolar junction transistor. The primary function of BJT is to increase the strength of a weak signal, i.e., it acts as an amplifier.
* Resistor: Two resistors of 2.2kΩ  is used in this project. A resistor controls the flow of the electrical current within a circuit.
* LED: This light emitting dioide is used as it produces light by passing the electric current through a semiconducting material.

# SWOT Analysis

## Strength

* Objects can be identified.
* It is effective solution and easier to build.
*  Cost is low.

## Weakness

* This can be only used for solid objects detection. For liquid objects, IR sensors are used.

## Opportunities
* This system has a lot of scope in automative industries. It is used in vehicles as a safety measure. 
* It can also be used in driverless vehicle for detecting objects.

## Threats

* Any other noises in the frequency of which ultrasonic sensor works can cause disturbances in the sensor's output.

# 4W's and 1H

## What 
Obstacle setection by measuring the distance of obstacle with the help of HC-SR04 Ultrasounic sensor, ATMEGA328 microcontroller, LCD Display and I2C bus.

## Where
It is used in automative industries.

## Why
It is used as a saafety measure and for comfortness of the users.

## When
It is used when there is need to detect a object and get an idea of distace of the obstacles.

## How
It is operated using a microcontroller and ultrasonic sensore.

# Details of Requirements

## High Level Requirements
![image](https://user-images.githubusercontent.com/71258149/164974370-388490d8-2300-4bf7-b398-7508c09733c7.png)

## Low Level Requirments
![image](https://user-images.githubusercontent.com/71258149/164974404-f7a3890b-a090-4c72-929d-5fe28665c022.png)
