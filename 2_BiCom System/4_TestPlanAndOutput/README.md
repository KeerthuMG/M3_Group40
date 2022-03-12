# TestPlanAndOutput
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

