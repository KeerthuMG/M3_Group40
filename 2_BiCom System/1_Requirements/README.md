# About Bicom System 

# 1 Description 

This is the extension of the Remote Keyless Entry,as it is operated in single directional This Bicom system is operated in bi directional way. This project gives the information of the qualities of the car like Window status and Alarm status,car battery info.

## 1.1 5W's & 1H

![](https://github.com/KeerthuMG/M3_Group40/blob/main/2_BiCom%20System/6_ImagesAndVideos/2SW.jpg)

## 1.2 Swot Analysis 

![](https://github.com/KeerthuMG/M3_Group40/blob/main/2_BiCom%20System/6_ImagesAndVideos/1SW.jpg)

## 1.3 Advantages And Disadvantages

## Advantages

It adds extra security for the car.

We can have better access control

Easy for the usage and it also saves some time compared to the normal one.


## Disadvantages

Potential risk comes from the fact that your car’s engine won’t automatically switch off when you are out of range.

As the technology increases it supports more Vulnerablility.


# 2 Requirements

## High Level Requirements
|ID  |DESCRIPTION	STATUS                                   |
|:---|:----------------------------------------------------|
|HLR1|It shall print the Window Status|
|HLR2|It shall print Alarm Status |
|HLR3|It shall print Car Battery information |
|HLR4|It shall print Door Status |


## Low Level Requirement
|ID  |DESCRIPTION	STATUS                                                               |
|:---|:--------------------------------------------------------------------------------|
|LLR1|User shall press the button once |
|LLR2|User shall press the button twice |
|LLR3|Uer shall press the button thrice |
|LLR4|User shall press the button four times |

# 3 Architecture 

# Test Plan And Output

## High Level test plan 

|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|HLTP1     |Window Status         |User press button once | Shall print Window Status        | Shall print Window Sttus              |PASS  |
|HLTP2     |Car Alarm Status      |User press button twice|Shall print Alarm Status | Shall print Alarm Status | PASS |
|HLTP3     |Car Battery Info      |User press button thrice|Shall print Battery Status | Shall print Battery Status | PASS |
|HLTP4     |Door Satus           |User press button four times|Shall print Door Stauts | Shall print Door Status | PASS |

## Low Level test plan 

| TEST ID | TEST CASE OBJECTIVE | INPUT DATA | EXPECTED OUTPUT | ACTUAL OUTPUT | STATUS |
|---------|---------------------|------------|-----------------|---------------|--------|
|LLTP1|Window Status | User press button once | Shall ON all the LED's| Shall ON all the LED's | PASS |
|LLTP2|Car Alarm Status | User press button twice | Shall OFF all the LED's | Shall OFF all the LED's | PASS |
|LLTP3|Car Battery Info | User press button thrice | Shall ON all the LED's once clockwise | Shall ON all the LED's once clockwise | PASS |
|LLTP4|Door Status | User press button four times | Shall OFF all the LED's once anticlockwise | Shall OFF all the LED's once anticloclwise | PASS |
