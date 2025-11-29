# iDrone-Project
# Hexacopter Frame Prototype & Flight Control System – iDrone Project

This project documents the end-to-end development of a custom hexacopter drone, covering structural design, electronics integration, and closed-loop flight control development.

---

## 🚁 Mechanical & Structural Design
- Created a complete **hexacopter frame prototype** using lightweight composite plates and aluminum standoffs.  
- Performed **mass balancing** and **center-of-gravity optimization** to ensure stable flight dynamics.  
- Designed motor arms with **vibration-damping features** to reduce IMU noise and improve controller accuracy.  
- Conducted structural checks for **bending**, **torsion**, and **frame resonance** during dynamic flight.

---

## 🔌 Powertrain & Electronics Integration
- Installed six **BLDC motors** and **ESCs** with a custom power-distribution layout for efficient current routing.  
- Integrated the full avionics stack: **flight controller**, **GPS**, **radio receiver**, **IMU sensors**, and **battery management system**.  
- Calibrated motors, ESC timing, and throttle curves to ensure **uniform thrust** across all six rotors.

---

## 🧠 Flight Control Architecture
- Implemented a multi-loop **PID-based control system** governing roll, pitch, yaw, and altitude.  
- Built a **sensor fusion pipeline** using accelerometer and gyroscope data (Complementary or Kalman Filter).  
- Developed custom **motor-mixing logic** optimized for hexacopter geometry.  
- Tuned proportional and derivative gains through iterative **hover and maneuver tests**.

---

## ⚖️ Balancing & Stabilization System
- Designed real-time algorithms to continuously adjust motor speeds and compensate for external disturbances.  
- Achieved stable hover, smooth maneuverability, and fast recovery from roll/pitch/yaw deviations.  
- Validated performance using **test flights**, **black-box logs**, and **vibration analysis** to refine controller performance.

---

Feel free to explore the code, schematics, and design files included in this repository!
