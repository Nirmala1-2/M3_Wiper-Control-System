# Introduction
 * This Project is an __Wiper control (WCS) system__,a wiper control system for an automotive wiper controls the operational speed of a wiper in accordance with rain conditions.It useful in the automotive unit the main purpose of the system is to clean the windscreen sufficiently to provide suitable visibility at all times.
 * we are trying to simulate this project on stmcube 32 IDE

# COMPONENTS AND SUPPLIES:
1. STM32F407 Discovery Board
2. Push Button
3. LEDs
4. Resistors
5. Power Supply

# ADVANTAGES:
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* It is quite simple to use.
* As a consequence, less energy is consumed.
* Rain sensor-based systems are extremely simple to install.
* Individual rain sensors are fairly inexpensive.

# Disadvantages:
* When water falls squarely on the rain sensor, the mechanism activates.
* The entire system cost rises when more components, including a rain sensor, are required.
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain. 

## 4W's & 1H and S.W.O.T analysis is in the below table 

# | 4W's & 1H | 
 __What__  
wiper control system (WCS) 

 __Where__ 
 
 Inside and outside the car

__When__   
When the weather condition is bad (like in rain and snow) the wiper is activate and clean the car window 

__Who__  
Who is driving or controlling the car 

__How__   
By using STM like by multiple pushes on a button

# | SWOT ANALYSIS | 

__Strengths__ 

* No human interaction with car
* Manages all commands with one key automatically


__Weaknesses__

* Unable to monitor status of car
* Range is limited
* Wait for certain time after every command to press new command 


__Opportunities__

* The Scope of this sytem is huge in automation or car control
* Less cost

__Threats__

* When new command is given without completing the current command it will not take current command 
---

## Requirements


### High Level Requirements

| ID | High Level Requirements |
| -------- | -------------- |
| HLR1 | It will start the car|
| HLR2 | It will start the wiper |
| HLR3 | It shall see the speed of the wiper work |
| HLR4 | It will stop the wiper |
| HLR5 | It will stop the car |

### Low Level Requirements

| ID | Low Level Requirements for HLR1|     
| ----- | ----- | 
| LLR1.1 | If the User button is pressed Once, the red LED will be on |      

| ID | Low Level Requirements for HLR2|
| ----- | ----- |
| LLR2.1 | If the User Button is pressed TWICE, Blue,Green,Orange LED's come ON at a time with set of frequency |

| ID | Low Level Requirements for HLR3| 
| -------- | -------------- |
| LLR3.1 |  If the User Button is pressed THIRD time, ON All LED's in CLOCKWISE manner an speeed will increase |  

| ID | Low Level Requirements for HLR4|
| -------- | -------------- |
| LLR4.1 | If the User Button is pressed FOURTH time ,all LED's on anticlock manner |

| ID | Low Level Requirements for HLR5|
| -------- | -------------- |
| LLR5.1 | If the User Button is pressed FIFTH times, the red LED will be off |

# OUTPUT IMAGES
1. User button is hold  for two seconds,the red LED is on
![ENGINE ON STATE](https://user-images.githubusercontent.com/101312396/168205845-9855cb85-3c2a-49ee-9e32-86cdc944a7c0.png)
2. Wiper Speed is LOW
![LOW](https://user-images.githubusercontent.com/101312396/168206233-b2fbccf2-1df2-4b97-9127-4e99626506cd.png)
3. Wiper Speed is MEDIUM

![G](https://user-images.githubusercontent.com/101312396/168206571-cfa61e88-18c1-4db7-a97f-23284b343cbe.png)

4. Wiper Speed is HIGH
![HIGH](https://user-images.githubusercontent.com/101312396/168206810-c69e4b0d-28b0-4ef4-8191-a3806236dbae.png)
5. User button is pressed and hold for 2 seconds, the red LED is off
![OFF](https://user-images.githubusercontent.com/101312396/168207080-f499c980-b029-48a1-becf-b28a336b77ce.png)
