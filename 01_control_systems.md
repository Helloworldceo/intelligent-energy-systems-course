# Project 1 Guide – Control Systems (Smart HVAC)

**Repository:** https://github.com/Helloworldceo/smart-hvac-control-system

## Stages Covered

1. Fundamentals (system, plant, sensor, actuator, feedback, setpoint, error)
2. ON/OFF controller + oscillation demonstration
3. First-order mathematical model of a room
4. Proportional control
5. PI and full PID (from scratch, with anti-windup and derivative filtering)
6. Disturbances (outdoor temperature, door opening, occupancy)
7. Metrics & visualization
8. Clean packaging

## Key Equations

**Room model:**
```
C * dT/dt = (T_out - T)/R + P_heater + P_disturbance
```

**PID:**
```
u(t) = Kp*e(t) + Ki*∫e(τ)dτ + Kd*de/dt
```

## How to study this project

1. Read `docs/mathematical_model.md` and `docs/controllers.md`
2. Run `python -m src.main`
3. Change controller gains in `src/main.py` and re-run
4. Disable disturbances and observe ideal step responses
5. Look at the metrics table and interpret rise time / overshoot / energy

## Suggested experiments

- Sweep Kp for pure P control and plot overshoot vs Kp
- Compare energy consumption of ON/OFF vs PID under the same disturbance profile
- Add a second thermal mass (two-room model) as an extension
