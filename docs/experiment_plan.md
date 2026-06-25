# Experiment Plan

## Objective

The experiment aims to evaluate whether external motion capture data can support or trigger a controlled point landing response for a small fixed-wing aircraft model.

## Proposed Experimental Workflow

```text
1. Prepare aircraft model and reflective markers
2. Calibrate Vicon / Qualisys motion capture system
3. Launch the aircraft using a repeatable catapult-style method
4. Record position and orientation data
5. Analyse trajectory, speed, pitch angle, and landing point
6. Add servo-controlled elevator or landing trigger
7. Compare landing results before and after trigger control
```

## Data to Record

The key data to record includes:

- time
- x, y, z position
- roll, pitch, yaw or quaternion orientation
- estimated velocity
- trigger time
- servo angle or command
- final landing position
- success or failure of landing/capture

## Evaluation Metrics

Potential metrics include:

### Landing Error

Distance between final landing/capture point and target point.

### Velocity Reduction

Comparison of aircraft speed before and after the trigger event.

### Pitch Response

Change in pitch angle after elevator actuation.

### Trigger Timing

Timing between motion capture detection, trigger command, servo response, and landing/capture.

### Success Rate

Percentage of trials that successfully achieve the target landing or capture condition.

## Initial Test Stages

### Stage 1: Passive Flight Test

Launch the aircraft without active elevator control and record the natural trajectory.

### Stage 2: Elevator Installation Test

Install a movable elevator and check whether the servo can reliably change its angle.

### Stage 3: Trigger Test

Use a simple trigger rule based on distance or time to activate the elevator or landing mechanism.

### Stage 4: Repeated Trials

Run multiple launches and compare landing accuracy and repeatability.
