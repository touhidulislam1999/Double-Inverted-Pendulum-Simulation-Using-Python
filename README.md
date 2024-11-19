# 🎢 Double-Inverted Pendulum Simulation Using Python

The double inverted pendulum is a challenging and nonlinear mechanical system that exhibits complex and chaotic dynamics. This project simulates the behavior of this fascinating system using Python, providing insights into its applications in robotics, aerospace engineering, and physics.

---

## 📜 **Introduction**
A double inverted pendulum consists of two pendulums, where the second pendulum is attached to the end of the first. Each pendulum swings under the influence of gravity, creating a highly unstable and nonlinear system. Due to its intricate dynamics, the double inverted pendulum is widely used as a benchmark problem in:
- **Control Theory**
- **Robotics Research**
- **Physics Instruction**
- **Aerospace Engineering**

### System Description:
- **Masses:** Pendulum 1 and Pendulum 2 have masses \( m_1 \) and \( m_2 \), respectively.
- **Lengths:** Their respective lengths are \( l_1 \) and \( l_2 \).
- **Angles:** Pendulum 1 forms an angle \( \theta_1 \) with the x-axis, and Pendulum 2 forms \( \theta_2 \) relative to Pendulum 1.

![Double Inverted Pendulum Diagram](https://github.com/user-attachments/assets/3457b429-0038-46c1-a969-4a8d756d60fc)

---

## 📐 **Derivation of Dynamics**

### **Kinetic Energy Calculation**
The kinetic energy (\( K \)) is calculated by summing the kinetic energies of the two masses. Using trigonometry to relate angular velocities (\( \dot{\theta}_1 \) and \( \dot{\theta}_2 \)), the total kinetic energy is:

![Kinetic Energy Formula](https://github.com/user-attachments/assets/c760b739-320e-4b1a-abb6-a3bf0d4a08ae)

---

### **Potential Energy Calculation**
The potential energy (\( P \)) is derived as the sum of the potential energies of the two pendulums, relative to their heights:

![Potential Energy Formula](https://github.com/user-attachments/assets/f16ff012-4e2d-4e99-9197-323118e838b3)

---

### **Lagrangian and Equations of Motion**
The Lagrangian (\( L \)) of the system is calculated as the difference between kinetic and potential energy:
\[
L = K - P
\]

Using **Lagrange's Equations**, the equations of motion for the double inverted pendulum are derived as follows:

![Lagrange Equation](https://github.com/user-attachments/assets/9c9cb5a2-f89a-4463-8f7c-ef1d9b0d8840)

These equations describe the dynamics of the system and form the basis for analyzing its behavior and designing control strategies.

---

## 🎥 **Simulation Results**

This project simulates the double inverted pendulum using Python and visualizes its chaotic motion. Below is the simulation result presented in a GIF format:

![Simulation GIF](https://github.com/user-attachments/assets/9ca89b28-0fc5-4225-a0fe-b7d328a47013)

---

## 📚 **Applications**
- **Control System Design:** Benchmark for advanced control algorithms.
- **Robotics:** Balancing systems and humanoid robots.
- **Aerospace Engineering:** Stabilization and trajectory prediction.
- **Physics Education:** Illustrating nonlinear dynamics and chaos theory.

---

## 🛠️ **How to Use**
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/touhidulislam1999/Double-Inverted-Pendulum-Simulation-Using-Python.git
