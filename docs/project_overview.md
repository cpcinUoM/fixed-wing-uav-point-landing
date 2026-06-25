# Project Overview

## Working Title

**Point Landing of Fixed-Wing UAVs**

## Project Aim

The aim of this project is to investigate a practical point landing approach for a small fixed-wing aircraft model. Instead of focusing on long-range autonomous flight, the project focuses on the final approach and landing/capture phase.

A catapult-style launch or repeatable external launch method will be used to provide an initial forward velocity. The aircraft trajectory will then be measured using an external motion capture system such as Vicon or portable Qualisys. The captured position and orientation data can be used to analyse the aircraft motion and determine suitable trigger conditions for elevator actuation or a landing/capture mechanism.

## System Concept

```text
Catapult launch
        ↓
Fixed-wing aircraft model
        ↓
Vicon / Qualisys motion capture
        ↓
Position and orientation measurement
        ↓
Trigger logic / controller
        ↓
Servo-controlled elevator or landing mechanism
        ↓
Point landing / capture evaluation
```

## Scope

This project is not intended to develop a full autonomous fixed-wing autopilot. The main focus is on:

- repeatable launch behaviour
- external motion capture tracking
- final approach trajectory analysis
- elevator or servo-triggered response
- landing position accuracy
- capture or stopping performance

## Current Physical Prototype

The current aircraft model is a small foam-board fixed-wing glider. It uses a simple high-wing configuration and is intended for indoor testing. Future improvements may include:

- adjustable elevator
- servo installation
- reflective marker mounting plate
- centre of gravity adjustment
- landing hook or capture interface
- reinforced wing and tail structure

## Expected Outcome

The expected outcome is a working experimental setup that can measure the aircraft trajectory and evaluate whether a controlled trigger action can improve point landing accuracy or repeatability.
