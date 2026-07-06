# Robotic Dog Mechanical Design

## Overview
This project presents an initial 3D mechanical design of a robotic dog created using Tinkercad. The design focuses on the basic mechanical principles required for a quadruped robot to stand and walk.

## Design Features
- Rectangular rigid body used as the main frame.
- Four legs connected to the main body.
- Two joints per leg: a hip joint and a knee joint.
- Two degrees of freedom (2 DOF) per leg and 8 DOF in total.
- Servo motors selected for controlled rotational movement at the joints.
- Flat feet used to improve contact with the ground and support stability.

## Torque Calculation
An initial torque calculation was performed for the hip joint.

Assumptions:
- Total robot mass = 1 kg
- Weight is equally distributed among four legs
- Mass supported by one leg = 0.25 kg
- Distance from the hip joint to the assumed point of force application = 0.03 m

Force:

`F = mg`

`F = 0.25 × 9.81 = 2.45 N`

Torque:

`τ = F × r`

`τ = 2.45 × 0.03 = 0.0735 N·m ≈ 0.074 N·m`

The minimum initial torque required at the hip joint is approximately **0.074 N·m** under static conditions. A higher-torque motor should be selected in a real design to account for leg weight, acceleration, friction, and a safety factor.

## Stability and Center of Gravity
The four legs are distributed around the rectangular body to provide a wide support area. The center of gravity is assumed to be near the middle of the main body. Keeping the center of gravity within the support area formed by the four feet helps reduce the risk of tipping.

## Proposed Walking Method
A slow walking gait is proposed. One leg moves at a time while the other three feet remain in contact with the ground to maintain stability. The hip and knee servo motors move the leg forward and then place the foot back on the ground.

## Expected Mechanical Challenges
Possible mechanical challenges include:
- Insufficient motor torque
- High friction at the joints
- Poor leg alignment
- Instability during walking
- Stress on the frame and joints due to repeated movement

## Tools
- Tinkercad
- Microsoft Word

## Project Report
The complete mechanical design report is available in this repository as a PDF file.

## Designed by
**Aram Alhejaili**
