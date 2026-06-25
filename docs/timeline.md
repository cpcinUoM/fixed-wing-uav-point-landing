# Project Timeline

Target completion date: **24 August**

## Overall Plan

| Period | Main Task | Expected Output |
|---|---|---|
| Week 1 | Confirm sensing setup | Decide between Vicon and portable Qualisys |
| Week 2 | Motion capture familiarisation | Record basic position and orientation data |
| Week 3 | Aircraft model improvement | Install elevator, servo, and marker mount |
| Week 4 | Passive launch testing | Collect baseline trajectory data |
| Week 5 | Trigger logic development | Define trigger rule based on distance, speed, or time |
| Week 6 | Servo/elevator testing | Validate servo response and elevator angle |
| Week 7 | Integrated flight tests | Test launch, tracking, trigger, and landing sequence |
| Week 8 | Data analysis | Plot trajectory, velocity, pitch, landing error |
| Week 9 | Dissertation writing | Write methodology, results, discussion |
| Final week | Final review and submission preparation | Figures, videos, final report polishing |

## Immediate Tasks

The current priority tasks are:

1. Confirm whether Vicon or portable Qualisys will be used.
2. Arrange a short training or demonstration session for the motion capture system.
3. Add reflective marker mounting points to the aircraft.
4. Measure and adjust the centre of gravity.
5. Design and install a simple elevator mechanism.
6. Plan a repeatable catapult-style launch method.
7. Record initial passive flight data.

## Notes

ROS2 and Unity are optional at this stage. They should only be added if the core experimental workflow is already working.

The priority is:

```text
Motion capture data → Python analysis → trigger logic → servo/elevator → landing evaluation
```
