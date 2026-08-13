# autonomous-rocket-flight-and-landing-simulation
MATLAB simulation of autonomous rocket ascent, hover, controlled descent, and landing using PID-based phase control.



A MATLAB simulation of a rocket's vertical motion using PID control and phase-based control for autonomous ascent, hover, and descent.

## Project Overview

The project models a rocket moving vertically under gravity and thrust. A PID controller adjusts the thrust to control the rocket's altitude and velocity.

The flight is divided into three phases:

- **Ascent:** The rocket rises toward the target altitude of 100 m.
- **Hover:** The rocket maintains approximately 100 m altitude.
- **Descent:** The controller switches to velocity control for a controlled downward motion.

The simulation includes integral windup protection, derivative filtering, velocity damping, gravity compensation, and thrust limits.

## Files

- `main_simulation.m` — MATLAB simulation code
- `main_simulation.mlx` — MATLAB Live Script
- `altitude_vs_time.png` — Altitude response
- `velocity_vs_time.png` — Velocity response
- `report.docx` — Detailed project report

## Results

The simulation demonstrates controlled ascent, stabilization near the target altitude, and a gradual descent.

## Requirements

- MATLAB

Run `main_simulation.m` or open `main_simulation.mlx` in MATLAB to reproduce the simulation.

## Documentation

For the complete mathematical model, control strategy, implementation details, results, and discussion, see **`report.docx`**.
