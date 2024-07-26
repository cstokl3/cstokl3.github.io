---
layout: page
title: Implementing Object Spawning and Environment Adaptation in a VR Robot Learning Project
subtitle: Final Project Poster
cover-img: /assets/img/path_03.png
thumbnail-img: /assets/img/unityarm_thumbnail.png
share-img: /assets/img/path_03.png
author: Caroline Stoklosinski
---

# Implementing Object Spawning and Environment Adaptation in a VR Robot Learning Project

## Authors and Affiliations
- **Caroline Stoklosinski**, The University of Illinois at Urbana-Champaign

## Introduction
### Background
The larger VR project aims to implement a UR5 robot arm in a virtual environment, where the robot can learn from a user interacting with it.

### Objectives
This summer, my project focused on adding a subset of functionalities to the larger VR project:
1. Creating new object spawns that the robot can use (e.g., coffee cup, laptop, knife).
2. Changing the environment to a kitchen, office room, or living room based on the presented object.
3. Implementing a gripper joint for the user to pick up and move the spawned items in the virtual environment.

## Methods
### Design/Procedure
The project was divided into three main tasks:
1. **Object Spawning:** Created 3D models of various objects (coffee cup, laptop, knife) and integrated them into the VR environment.
2. **Environment Adaptation:** Developed scripts to switch the environment (kitchen, office room, living room) based on the object presented to the robot.
3. **Gripper Joint Implementation:** Enhanced the VR interaction by adding a gripper joint to allow the user to pick up and move objects within the virtual space.

### Materials
- VR development software (e.g., Unity, Unreal Engine)
- UR5 robot arm simulation tools

### Participants
N/A

## Results
### Data Presentation
![Robot Gripper](assests/img/gripper_screenshot.png)
Screenshot of the gripper on UR5 robot arm.


### Analysis
- Successfully integrated object spawning, environment adaptation, and gripper joint functionalities.
- The VR robot can now interact with various objects and adapt to different environments, enhancing its learning capabilities from user interactions.

## Discussion
### Interpretation
The added functionalities significantly improve the versatility and learning potential of the VR robot. The robot can now handle diverse objects and operate in different settings, making it more adaptable to real-world scenarios.

### Limitations
- The project was limited to a subset of objects and environments.
- Further testing is needed to ensure seamless interaction across all possible scenarios.

## Conclusion
### Summary
My parts of this VR summer project successfully enhanced the VR robot learning project by adding object spawning, environment adaptation, and gripper joint functionalities.

### Implications
These enhancements allow the VR robot to learn from a wider range of interactions, potentially leading to more advanced and adaptable robotic systems. This system will allow for training robots in a virtual environment to later be implemented in the real world - such as used for assisting those who are older/have disabilities with any task they may need completed - things such as cutting ingredients, assisting with lifting items, etc.

### Future Research
- Expanding the range of objects and environments.
- Testing the system with more complex interactions and scenarios.
- Integrating more advanced machine learning algorithms for improved learning from user interactions.

## Acknowledgments
A special thank you to my mentors, Courtney McBeth Isaac Ngui; my PI's Dr. Nancy Amato and Dr. Marco Morales for supporting this project, and my fellow students on this project Grace He and André Corrêa Santos. 

## Contact Information
For further inquiries, please contact:
- **Email:** cstokl3@illinois.edu

<!-- Add any custom styling if needed -->
<style>
  .poster-section {
    margin-bottom: 20px;
  }
  .poster-section h2 {
    color: #2E86C1;
  }
  .poster-section h3 {
    color: #2874A6;
  }
</style>
