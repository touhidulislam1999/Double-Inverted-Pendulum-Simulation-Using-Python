# Double-Inverted-Pendulum-Simulation-Using-Python
The double inverted pendulum is a complex, unstable, and nonlinear mechanical device with two connected pendulums swinging vertically under gravity. It's a benchmark problem in control theory and robotics study, with applications in robotics, aerospace engineering, and physics instruction.

# Introduction:
A mechanical device called a double inverted pendulum consists of two pendulums, one of which is connected to the end of the other. Under the pull of gravity, each pendulum is allowed to swing in a vertical plane. A extremely unstable and nonlinear system that displays complex and chaotic behavior is the double inverted pendulum. Due to its complex dynamics and the difficulty in controlling it, it is frequently used as a benchmark problem for control theory and robotics study. Applications for the double inverted pendulum include robotics, aeronautical engineering, and physics instruction.

![image](https://github.com/user-attachments/assets/3457b429-0038-46c1-a969-4a8d756d60fc)

Here if Figure 1: there are two pendulums with mass of the bobs m1 and m2 and both having an amplitude of l1 and l2 respectively. Pendulum 1 has created an angle of θ1 with x-axis and pendulum 2 has created an angle of θ2 with the length of pendulum 1.

# Derivation:
**Kinetic Energy Calculation:**
The kinetic energy of the system is the sum of the kinetic energies of the two masses. The velocity of each mass can be expressed as a function of the angular velocities of the links using trigonometry. The kinetic energy is then given by the sum of the kinetic energies of the two masses:

![image](https://github.com/user-attachments/assets/c760b739-320e-4b1a-abb6-a3bf0d4a08ae)
𝜃̇1 and 𝜃̇2 are the angular velocities of the first and second links respectively.

# Potential Energy Calculation:
The potential energy of the system is the sum of the potential energies of the two masses, given by:

![image](https://github.com/user-attachments/assets/f16ff012-4e2d-4e99-9197-323118e838b3)
where g is the acceleration due to gravity.

# Calculate Lagrangian:
The Lagrangian, L is the difference between the kinetic energy and potential energy of the system

                        **L = K-P**
# Apply of Lagrange’s Equations:
Lagrange's equations can be used to derive the equations of motion for the system:
![image](https://github.com/user-attachments/assets/9c9cb5a2-f89a-4463-8f7c-ef1d9b0d8840)

These equations describe the dynamics of the double inverted pendulum, and can be used to analyze its behavior and design control strategies.

We simulate the double inverted pendulum system using python and here is our result in GIF format: 
![image](https://github.com/user-attachments/assets/9ca89b28-0fc5-4225-a0fe-b7d328a47013)

# References:
1. https://www3.math.tuberlin.de/Vorlesungen/SoSe12/Kontrolltheorie/matlab/inverted_pendulu
m.pdf
                        
