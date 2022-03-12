# Test Plan And Output

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
