# Sensor Selection

## Primary Sensor Option: Vicon / Qualisys Motion Capture

The preferred sensing approach is to use an external optical motion capture system, such as **Vicon** or the portable **Qualisys** system available in the laboratory.

Both systems can provide:

- 3D position of the aircraft model
- orientation / attitude data
- trajectory over time
- velocity estimation through data processing

This is suitable for the project because the experiment is expected to be conducted indoors and focuses on the final approach and landing phase.

## Why Motion Capture Is Suitable

Motion capture is suitable because point landing requires accurate knowledge of the aircraft position relative to the landing target. Compared with onboard-only sensors, external motion capture avoids drift and provides more reliable position and attitude information in an indoor environment.

## Backup Sensor Option: AprilTag / ArUco

If the motion capture system is unavailable or difficult to access, the backup option is to use an external camera with AprilTag or ArUco marker tracking.

A possible backup setup is:

```text
External camera
        ↓
AprilTag / ArUco marker on aircraft
        ↓
Pose estimation using Python / OpenCV
        ↓
Trigger logic
        ↓
Servo or landing mechanism
```

## IMU Decision

An IMU is not selected as the main sensing method because it cannot directly provide accurate global position. Position estimation from acceleration integration is prone to drift, which is not ideal for precise point landing.

The IMU may still be discussed in the literature review as a common onboard sensing option, but it is not required for the current experimental setup.

## Current Decision

```text
Plan A: Vicon / portable Qualisys motion capture
Plan B: AprilTag or ArUco with external camera
Not selected as main sensor: IMU-only sensing
```
