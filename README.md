# Fixed-Wing UAV Point Landing

This repository documents the development of an MSc dissertation project on **Point Landing of Fixed-Wing UAVs** at the University of Manchester.

The project investigates how a small fixed-wing aircraft model can be launched using a catapult-like method, tracked using an external motion capture system, and guided or triggered to achieve a precise point landing or capture.

## Project Direction

The current technical direction is:

- **Aircraft type:** small foam-board fixed-wing glider / UAV model
- **Launch method:** catapult-style launch or repeatable external launch mechanism
- **Primary sensing option:** Vicon or portable Qualisys motion capture system
- **Backup sensing option:** AprilTag / ArUco marker tracking using an external camera
- **Main objective:** use external position and orientation data to analyse approach trajectory, trigger timing, elevator response, and landing accuracy
- **Actuation:** servo-controlled elevator and/or landing/capture trigger mechanism

## Repository Structure

```text
fixed-wing-uav-point-landing/
├── README.md
├── docs/
│   ├── project_overview.md
│   ├── sensor_selection.md
│   ├── experiment_plan.md
│   └── timeline.md
├── src/
│   ├── motion_capture/
│   ├── servo_control/
│   └── data_analysis/
├── data/
├── cad/
├── images/
└── references/
```

## Main Research Focus

The project focuses on the final approach and point landing phase rather than full autonomous long-range flight. The key research question is:

> Can external motion capture data be used to support or trigger a controlled point landing mechanism for a small fixed-wing UAV model?

## Key Evaluation Metrics

Potential evaluation metrics include:

- Landing position error
- Velocity before and after trigger
- Pitch angle during final approach
- Trigger timing
- Success rate of landing/capture
- Repeatability of launch and landing trajectory

## Notes

This repository will be updated as the dissertation progresses, including experimental setup, motion capture data processing, servo control code, analysis scripts, CAD files, and result figures.
