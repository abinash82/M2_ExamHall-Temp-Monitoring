## Requirements
As the outside temperature varies, it may affect our room temperature. So there is a need for technique to control the temperature of the exam hall according to the number of students presented in the exam hall even if the outside temperature varies. This exam hall Temperature Monitoring system Controller Using Atmega328 Microcontroller overcomes this problem. The system allows to regulates the specific temperature of the exam hall and monitor the overall temperature through the LCD.


## Introduction
The Exam Hall Temperature Monitoring system is basically used to monitor the temperature of the Exam hall according to the number of students presented. When the students are presented, the button sensor gets activated. After that, the exam hall analyser gets access to turn on the heater.The temperature sensor buttons keeps monitoring the temperature of the exam hall on the basis of students available in the hall and sends the analog value to the ATmega328 microcontroller. The microcontroller processes the analog input of the temperature sensor button and outputs a temperature value through serial communication. All the activities of the regulating systen is performed with a microcontroller called Atmega328 and monitored by CRO serial communication o/p..

## Features
 - The System will sense whether the student's seats is occupied or not.
 - The user who is regulating the sytem of the exam hall has the access to modify the temperature in the exam hall on the basis of students available.
 - As per the count of students in the exam hall, Heater will generate the heat accordingly.
 - It is best for cold Countries for heat control and for normal countries it can be used as both increasing or decreasing the heatness or coldness.
 - Low cost instalzation and can be redesigned according to the needs.
simulation and prototypical Approach can be processed.
 - Simulation
 - The functionality of the exam hall Temperature Monitoring system is coded in embedded c through visual studio and the working of this regulating system is performed using simulation software called SimulIDE.

## SWOT Analysis
## Strengths
 - It is User Friendly
 - Easy to alter the temperature inside the exam hall according to the needs.
 - Low power consumption. 
## Weakness
 - Its cannot be connected wirelessly and its should be managed and maintained regularly.
## Opportunities
 - It can applied commercially by implementing along with both the Heater and AC for performance according to the temperature.
## Threats
 - Not suitable for average or high temperature places.
 - Maintaince of the system is high.
## High Level Requirements
RID |  Description | Status |
|---| :-------: | :------: |
| HLR1   |ATmega328 |Implemented|
|HRL2         |  Embedded C | Implemented           |
|HLR3| Arduino IDE|  Implemented|
|HLR4|Visual studio|  Implemented|
|HLR5| SimulIDE| Implemented|
## Low level Requirements
 RID |  Description | Status |
|---| :-------: | :------: |
| LLR1   |Temperature Sensor |Implemented|
|LRL2         |  Button sensor | Implemented           |
|LLR3| serial communication o/p|  Implemented|
|LLR4| Power Supply|  Implemented|


## 4W's and 1'H
## Why:

The main concept of building this project is to easily regulate the temperature of the exam hall on the basis of the students the presented in the class to generate an output signal.

## What:

This project is all about the monitoring the overall temperature of the exam hall and gives the data to control the temeprature inside the class.

## Where:

This project is best for exam hall,computer lab,physics lab, biology lab and library because these places are covered with crowds and due to this temperature may rise.this project is used to regulate the overall temeprature of the class.

## When:

This project is going to be deployed on 22/04/2022.

## How:

This project includes push buttons according to number of students presented in the class and according to it manages increasing or decreasing of the temperature in the exam hall and sends analog data to ATmega324 controller and monitored using LCD.
