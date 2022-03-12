# RKE (Remote Keyless Entry)

# 1. INTRODUCTION 

## 1.1 Description 

RKE (remote keyless entry) is an electronic access control system that may be operated from a distance. RKEs, which are commonly used to remotely lock or unlock doors, need the end user to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock. The action is usually performed by pressing a button on a physical fob. The RKE systems for cars can also be used to control the vehicle's ignition system, security alarm, horn, and lights, in addition to locking and unlocking the doors. RKEs can also be used to control access to specific areas of a building, such as garages. While RKE is not commonly used in buildings other than enterprises, it is used in some home automation and security systems.


## 1.2 Software Requirements

 * Cygwin : Cygwin is a POSIX-Compatible programming and runtime environment that runs natively on Microsoft Windows.
             Under Cygwin, source code designed for Unix-like operating systems may be compiled with minimal modification and executed.
 * STM32CUBEIDE : The STM32 is a family of microcontroller ICs based on the 32-bit RISC ARM Cortex-M33F, Cortex-M7F, Cortex-M4F, Cortex-M3, Cortex-M0+, and Cortex-M0 cores.
 
 
## 1.3 SWOT Analysis



## 1.4 5W's & 1H




## 1.5 Requirements
## High Level Requirement

|ID  |DESCRIPTION                          |
|:---|:------------------------------------|
|HLR1|System shall be provided with wireless lock system | 
|HLR2|System shall be provided with wireless unlock system | 
|HLR3|System shall be provided with wireless alarm activation and deactivation system |
|HLR4|System shall be provided with light approach |


## Low  Level requirements 
|ID  |DESCRIPTION                                                                                      | 
|:---|:------------------------------------------------------------------------------------------------|
|LLR1|User shall press blue switch on for lock operation|
|LLR2|User shall press blue switch twice for unlock operation|
|LLR3|User shall press blue switch thrice for activation and deactivation of alarm |
|LLR4|User shall press blue switch four times for light approach operation |


## 1.6 Advantages

* It adds extra security for the car.
* We can have better access control(its handey)
* Easy for the usage and it also saves some time compared to the normal one.
    
## 1.7 Disadvantages

* There can be possibility of hackers to manpiulate.
* potential risk comes from the fact that your car’s engine won’t automatically switch off when you are out of range.
* As the technology increases it supports more Vulnerablility.

# 2. ARCHITECTURE



# 3. TEST PLAN AND OUTPUT

## High Level Test Plan 

|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|HLTP1    |For Car lock Function                     |User shall press the button once |Car locked            |Car locked              |PASS  |
|HLTP2    |For Car unlock Function                   |User shall press the button twice | Car unlocked          |Car unlocked          |PASS  |
|HLTP3     |For alarm activation/deactivation Function|User shall press the button thrice|Alarm activated/deactivated|Alarm activated/deactivated|PASS  |
|HLTP4     |For approach light Function               |User shall press the button four times|Light approach ON      |Light approach ON       |PASS  |


## Low Level Test Plan

|Test ID|	Description                 |Input	                         |Exp output                                                   |Actual Output                        |Status|
|:------|:----------------------------|:-------------------------------|:------------------------------------------------------------|:------------------------------------|:-----|
|LLR1	|Car lock  | 1 user button press |All LEDs will be ON  |All LEDs ON  |	PASS|
|LLR2  |Car unlock                   | 2 user button press  |All LEDs OFF|All LEDs OFF | PASS |
|LLR3	|Alarm activation/deactivation| 3 user button press|All LEDs ON Clockwise direction |All LEDs ON Clockwise direction |PASS|
|LLR4  |Approach light| 4 user button press|	All LEDs ON in Anticlockwise direction |All LEDs ON Anticlockwise direction | PASS |          

