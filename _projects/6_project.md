---
layout: page
title: Quadrotor Autonomy and External-Wrench Estimation
description: Autonomous flight and physically structured learning for external force and torque estimation.
importance: 1
category: research
related_publications: lei2026quadrotor
---

**Robotics Algorithm Engineer · Viterra Robotics · April – October 2026**

My work connected quadrotor simulation, onboard deployment, and real-world flight validation. I developed autonomous exploration and motion planning algorithms for complex, GPS-denied environments, alongside flight-dynamics identification and control-oriented modeling.

### External force and torque estimation

This research estimates the six-axis external wrench acting on a quadrotor from its motion and actuation. A central challenge is distinguishing external loads from errors in the vehicle's own dynamics model.

We use a physically structured residual model for shared inflow, rotor effectiveness, horizontal aerodynamic force, and aerodynamic moment. The model is identified from unloaded flight data and then held fixed inside an error-state Kalman filter, which estimates the remaining external forces and moments.

The method was evaluated in software-in-the-loop simulation and real flight, including comparisons against onboard six-axis force–torque sensor measurements and localized wind disturbances.

**Manuscript status:** To be submitted to IEEE Robotics and Automation Letters (RA-L).
