[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/6VRf8cDN)
# Virtual Museum Assignment

## Overview

In this assignment, you will develop a computer graphics project using **C++** and **OpenGL** to simulate a virtual museum environment. You will create a 3D room with realistic lighting, model 3D objects from provided images using Blender, and simulate a mobile robot equipped with a robot arm (or a similar scanning mechanism) that interacts with these objects. When an object is scanned, a pop-up screen will display detailed information about that object.

## Objectives

- **Scene Construction:**  
  Create a virtual museum room with at least one main light source. Extra points will be awarded for implementing additional spotlights.

- **3D Modeling:**  
  Model 5 museum objects (using images provided from Adana Museum) in Blender. Export these models and integrate them into your OpenGL scene.

- **Mobile Robot Simulation:**  
  Develop a mobile robot that navigates the room to visit and scan objects.  
  - The robot should be equipped with a robot arm or a scanning mechanism looks like an arm.  
  - Upon scanning an object, a pop-up UI should display information about that object.

- **User Interface:**  
  Create a UI to control the mobile platform, the robot arm, and the lighting (including light control switches for features such as spotlights).

## Project Requirements

- **Programming Language:** C++
- **Graphics Library:** OpenGL
- **3D Modeling Tool:** Blender (for modeling and exporting 3D objects)
- **UI Framework:** Either custom-built or a UI library (e.g., ImGui) as specified
- **Version Control:** Git/GitHub for project submission and collaboration

## Deliverables

1. **Source Code:**  
   Well-organized and documented C++ and OpenGL source code.

2. **3D Models:**  
   Blender files and exported models for the 5 museum objects.

3. **Executable:**  
   A buildable project that runs on the specified platform.

4. **Documentation:**  
   A detailed README (this document) explaining the project structure, build and run instructions, and details on controls and features.

5. **Demonstration Video (Optional/Bonus):**  
   A short video demonstrating the robot’s functionality and UI controls.

## Evaluation Criteria

- **Scene Realism:**  
  Quality of the 3D room, lighting effects, and the use of spotlights.

- **Robot Simulation:**  
  Functionality of the mobile robot, including navigation and scanning mechanics.

- **UI Implementation:**  
  Ease of use and functionality of the control interfaces for the robot and lighting.

- **Code Quality:**  
  Structure (OOP), clarity, and documentation of the source code.

- **Bonus Points:**  
  Extra features such as additional spotlights, enhanced physics for the robot arm, collision detection, advanced shading techniques, ray tracing etc.

## Suggested Workflow

1. ### Setup and Environment
   - Initialize your Git repository and project structure.
   - Set up your development environment with necessary libraries (OpenGL, GLM, GLEW/GLAD, etc.).

2. ### 3D Modeling
   - Use Blender to create and export the 5 museum object models.
   - Ensure the models are optimized for real-time rendering.

3. ### Scene and Lighting
   - Build the 3D room in OpenGL.
   - Implement the main light source and add additional spotlights for extra credit.

4. ### Robot and Interaction
   - Design and implement the mobile robot.
   - Develop the robot arm or scanning mechanism.
   - Program the scanning function to trigger a pop-up information screen when an object is scanned.

5. ### User Interface
   - Design a UI to control the robot’s movements and the robot arm.
   - Include buttons or switches for toggling lights (including spotlights).

6. ### Testing and Documentation
   - Test your project thoroughly.
   - Document your code and update this README with detailed build instructions, controls, and feature descriptions.
