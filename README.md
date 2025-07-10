# 5-DOF-Robot-Arm-3D-Design
 A five-degree-of-freedom (5-DOF) 3D robotic arm using Onshape.
This project contains a 3D model of a robotic arm with **5 mechanical components** representing **5 degrees of freedom**, designed using **Onshape** and exported as individual STL files for 3D printing.

## Components & Functions

1. **Base Platform**
   - Fixed, non-rotating base that provides structural support for the entire arm.
2. **Rotating Joint**
   - Moves between **0° and 180°**.
   - Controls vertical rotation of the upper arm (like an elbow joint).
3. **Upper Arm Link**
   - Connects the rotating joint to the wrist.
   - Free-moving in design, allows angular extension and positioning.
4. **Wrist Joint**
   - Interfaces between the arm and the gripper.
   - Free in movement, enables wrist-like articulation (pitch or roll).
5. **Gripper (End Effector)**
   - Designed to grab and hold objects.
   - Motion is free and customizable depending on external actuator.

## Notes
- All parts exported in `.STL` format, high resolution, binary format, and preprocessed for 3D printing.
- The model is modular and can be scaled or modified to suit servo-based control systems.
