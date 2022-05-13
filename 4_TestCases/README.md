# Test Cases

## High Level

| ID | Description | I/P | Expected O/P | Actual O/P | Pass/Fail |
| --- | ---------- | --- | ------------- | ---------- | ----------- |
| HL_1 | engine on | once button pressed | engine on |  engine on |  pass |
| HL_2 | engine off |  twice button pressed | engine off | engine off | pass |
| HL_3 | wiper on |  thrice button pressed | wiper on | on wiper in clockwise direction | pass |
| HL_4 | wiper off |  four times button pressed | wiper off | on wiper in anti-clockwise direction | pass |





## Low Level 

| ID | Description | I/P | Expected O/P | Actual O/P | Type Of Test |
| --- | ---------- | --- | ------------- | ---------- | ----------- |
| LL_1 | engine on | once button pressed | all led on |  all led on |  pass |
| LL_2 | engine off | twice button pressed | all led off |  all led off |  pass |
| LL_3 | wiper on | thrice button pressed | all led on once |  all led on |  pass |
| LL_4 | wiper off | four times button pressed | all led off once |  all led off |  pass |




