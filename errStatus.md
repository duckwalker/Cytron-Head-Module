# ERROR STATUS TABLE #

## Description ##
|bit 7|bit 6|bit 5|bit 4|bit 3|bit 2|bit 1|bit 0|
|:----|:----|:----|:----|:----|:----|:----|:----|
|     |     |     |     |     |Instruction     |Checksum     |Range  |


if HM.errStatus higher than 0 ,it was print out  HM Reading Error

if HM.errStatus equal to 0 ,it was print out your data


|Value| Error Status|
|:----|:------------|
|0    |No Error|
|1    |Range Error|
|2    |Checksum Error|
|3    |Range and Checksum Error|
|4    |Instruction Error|
|5    |Instruction and Range Error|
|6    |Instruction and Checksum Error|
|7    |Instruction,Checksum,Range Error|


