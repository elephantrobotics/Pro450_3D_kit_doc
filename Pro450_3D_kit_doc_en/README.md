# Pro450 3D Kit User Guide

<img src="../img/450_1.png" style="zoom: 50%;" />

## 1. Kit Overview

The myCobot Pro 450 is a compact, all-in-one, full-harmonic six-axis robotic arm. The harmonic reducer, servo motor, brakes, and controller are integrated into the joint module, eliminating the need for a separate control cabinet. Its small size allows for professional robotic applications. This time, we paired it with an industrial-grade 3D camera. Unlike ordinary 2D vision, it can acquire 3D point cloud information of objects, not only "seeing" objects but also determining their position and orientation in space. We used a set of randomly placed PVC pipes to build a typical industrial disordered sorting experiment. This fully validated the 3D perception, target matching, pose calculation, and robot grasping process in industrial vision sorting. The 3D camera first acquires the scene point cloud, identifies different types of workpieces through point cloud template matching, and calculates the target's spatial pose. The robotic arm moves to the grasping position based on the recognition results, completes the grasping, and then places different workpieces into the corresponding areas. The type, position, and orientation of the workpieces do not need to be neatly arranged in advance. This is precisely the complete logic of a robot in industrial unordered sorting, from "seeing" to "understanding space" and then to "performing grasping." From 3D vision to robot control, a desktop platform is used to learn and verify real-world industrial unordered sorting processes.

## 2. Workflow

After the program starts, it will automatically trigger the camera to take pictures and determine if there are any workpieces in the tray. If a workpiece is detected, the system will obtain the workpiece's pose and category information based on visual feedback, control the robotic arm to grasp it, and classify and place it in the appropriate location. If no workpiece is detected, the program will automatically terminate.

## 3. Kit List

|Item|Quantity|
|--|--|
|MyCobotPro450 Robotic Arm|1|
|3D Camera|1|
|Camera Flange|1|
|Single-Head Suction Pump|1|
|Map|1|
|Pattern|1|
|Sorting Box|2|
|PVC Workpieces|Several|

## 4. Introduction Follow the table of contents to build the Pro3D kit. 
First, refer to Chapter 1 for software environment setup and configure your computer's operating environment. Then, follow Chapter 2 to build the hardware. Next, follow Chapter 3 to test the functionality of each unit. Then, follow Chapter 4 for hand-eye calibration. Finally, follow Chapter 5 to run the Pro3D kit example program.

- [Pro450 3D Suite User Guide]()

  * [1 Software Environment Setup](./book1.md)

  * [2 Hardware Installation](./book2.md)

  * [3 Unit Testing](./book3.md)

  * [4 Hand-Eye Calibration](./hand_eye.md)

  * [5 Case Reproduction](./book4.md)

<!-- * [6 Extended Applications](./book5.md) -->

---

[← Previous Chapter](./1.1-introduction.md) | [Next Chapter →](./book1.md)