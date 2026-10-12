# Project Roadmap

## Phase 1 — Geometry and CAD
- [ ] Define base and moving-platform attachment points.
- [ ] Record actuator stroke and joint-angle limits.
- [ ] Build and review the SolidWorks assembly.
- [ ] Export approved reference images and neutral CAD files if permitted.

## Phase 2 — Kinematics
- [ ] Define coordinate frames and pose convention.
- [ ] Implement inverse kinematics.
- [ ] Check actuator lengths against mechanical limits.
- [ ] Validate with known poses and simple test cases.

## Phase 3 — MATLAB simulation
- [ ] Simulate platform poses and actuator lengths.
- [ ] Add motion profiles and external disturbance scenarios.
- [ ] Plot commanded vs. achieved pose and actuator response.

## Phase 4 — Sensing and control
- [ ] Select IMU and define its mounting frame.
- [ ] Implement orientation estimation and calibration.
- [ ] Compare candidate controllers in simulation.
- [ ] Measure orientation error, settling time, and overshoot.

## Phase 5 — Prototype validation
- [ ] Review safety limits and actuator constraints.
- [ ] Run low-speed tests before aggressive motion.
- [ ] Document repeatable experiments and results.
