# VR Classroom Builder

## Project Overview

The VR Classroom Builder is a virtual reality project designed to enhance educational experiences by simulating classroom layouts and promoting ergonomic considerations. This project aims to demonstrate proficiency in VR development and contribute to improving student learning environments.

## Objectives

The primary objectives of this project are:
1. To create a virtual reality environment that allows users to configure and arrange classroom furniture and electronic equipment.
2. To develop a system for assessing various classroom configurations based on ergonomic principles.
3. To implement interactive features that enable users to simulate student positions and navigate through the virtual classroom.

## Key features

### Virtual Classroom Configuration

- Users can freely place and arrange furniture and electronic equipment in the virtual classroom.
- Two basic classroom models are implemented, considering the positioning of essential structural elements:
	- Lighting points
	- Electrical outlets
	- Classroom capacity

### Ergonomic Rules

- Four mandatory ergonomic rules are implemented:
	1. Desks with computers must be at least 5 meters away from electrical outlets.
	2. The maximum distance to the board/projection screen should not exceed 10 meters.
	3. Additional rules can be defined and validated through contextual menus in the Virtual Reality experience.
	4. The system allows for solutions that do not meet the established rules.

### Furniture and Equipment

- Various models of desks and chairs;
- Desktop and laptop computers;
- Board/Projection screens for teachers.

### Development techniques

The project utilizes several VR development techniques:
1. Combination of freeform and directed techniques with "sockets" and grabbable objects.
2. Implementation of navigation strategies within the environment.
3. Addition of realistic elements to the scene (e.g., models from the asset store).
4. Dynamic addition of products/components for assembling multiple elements.

## Technical Implementation

### Software Tools

- Unity XR for:
	- Implementing grabbing/attaching objects
	- Defining a CameraRig for the operator
	- Defining Sockets for interactions with products and parts
	- Simulating a virtual reality environment
- Collision detection between objects and work surfaces using collision components on products.

### Evaluation Methodology

A virtual reality experience evaluation will be conducted based on scientific analysis procedures. The evaluation will use the Witmer and Singer (1998) Presence Questionnaire to assess user experiences across four categories:

1. Control Factors (CF)
2. Sensory Factors (SF)
3. Distraction Factors (DF)
4. Realism Factor (RF)

This evaluation will provide valuable insights into the effectiveness of the VR Classroom Builder in creating immersive and engaging educational experiences.