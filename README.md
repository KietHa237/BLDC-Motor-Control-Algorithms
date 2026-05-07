# ⚙️ BLDC Motor Control Strategy: PID vs. Fuzzy vs. FOC

This project explores three different control methodologies for Brushless DC (BLDC) motors, ranging from classic linear control to advanced vector control techniques.

## 🔬 Algorithms Overview

### 1. Proportional-Integral-Derivative (PID)
- **Method:** Trapezoidal (6-step) control.
- **Pros:** Simple to implement, low computational cost.
- **Cons:** High torque ripple and audible noise.

### 2. Fuzzy Logic Control (FLC)
- **Method:** Rule-based control (Mamdani/Sugeno).
- **Pros:** Robust against parameter variations and non-linearities.
- **Cons:** Requires expert knowledge to define membership functions and rules.

### 3. Field Oriented Control (FOC) - Vector Control
- **Method:** Clarke & Park transformations to decouple torque and flux.
- **Pros:** Smooth rotation at all speeds, high efficiency, and silent operation.
- **Cons:** Highly complex mathematics and requires high-speed MCU.



## 🛠 Tech Stack
- **Simulation:** MATLAB / Simulink.
- **Hardware Interface:** [STM32 / ESP32 / Arduino].
- **Sensors:** Hall Effect sensors or Encoder.

## 📂 Contents
- `/Simulink_Models`: `.slx` files comparing the three algorithms.
- `/Source_Code`: Implementation in C++ for embedded systems.
- `/Docs`: Mathematical derivations for Clarke and Park transformations.
