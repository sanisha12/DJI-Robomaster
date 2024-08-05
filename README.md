# Person Tracking and Object Detection Using Robomaster EP Core and YOLOv8

This project focuses on developing an advanced system for person tracking and object detection using the Robomaster EP Core robot and YOLOv8. As part of my Master's program's second semester course project, I aimed to explore the integration of robotics and computer vision. The project was divided into three main goals: navigating the robot from point A to point B, detecting and avoiding objects, and tracking a person.

## Project Objectives

### Navigate the Robot from Point A to Point B

The first goal was to program the Robomaster EP Core for autonomous navigation from a designated starting point (Point A) to a destination (Point B). This involved utilizing the robot's built-in motion control features and sensors for precise and efficient movement.

### Object Detection and Avoidance Using YOLOv8 and Sensors

The second objective aimed to enhance the robot's navigation capabilities by integrating object detection and avoidance. YOLOv8, a state-of-the-art object detection model, was used to identify obstacles in the robot's path. The robot's sensors measured distances to these objects, allowing the robot to adjust its path and avoid collisions.

### Person Tracking

The third objective was to create a system for tracking a person. YOLOv8 was utilized to detect and identify a specific individual. The Robomaster EP Core then used this information to follow the person, maintaining a safe distance and adjusting its trajectory in real-time.

## Tools and Technologies

- **Anaconda**: Used as the primary Python distribution and package manager, facilitating the setup of the development environment.
- **Visual Studio Code**: Employed as the integrated development environment (IDE) for coding and debugging.
- **Robomaster SDK**: Provided the necessary APIs and tools to control the Robomaster EP Core and integrate it with the detection and tracking systems.
- **YOLOv8**: Leveraged for its powerful real-time object detection capabilities, enabling the robot to detect and avoid obstacles, as well as track a person.

## Project Workflow

### Setup and Configuration

- Anaconda was used to create a virtual environment, ensuring all dependencies and packages required for the project were installed and managed efficiently.
- Visual Studio Code was configured with the necessary extensions and tools for Python development.

### Robot Navigation (Point A to Point B)

- Using the Robomaster SDK, a path was programmed for the robot to follow from Point A to Point B. The robot's sensors were utilized to ensure accurate navigation and obstacle avoidance.

### Object Detection and Avoidance

- YOLOv8 was integrated into the system to detect objects in the robot's path. The detected objects' coordinates were used in conjunction with the robot's sensors to calculate the distance and adjust the robot's path to avoid collisions.

### Person Tracking

- YOLOv8 was trained to detect and identify a specific person. The Robomaster EP Core was programmed to follow the person, using real-time data from the detection model to adjust its movement and maintain a safe distance.

## Results and Conclusion

The project successfully met all three objectives. The Robomaster EP Core was able to autonomously navigate from Point A to Point B, detect and avoid objects in its path, and effectively track a person. The integration of YOLOv8 with the Robomaster SDK proved to be a powerful combination, enabling advanced object detection and tracking capabilities. This project demonstrates the potential of combining robotics with computer vision for creating intelligent and autonomous systems.

## Future Work

Future improvements could include:

- Enhancing the robustness of the object detection and tracking system in various lighting conditions.
- Implementing more sophisticated path planning algorithms to improve navigation efficiency.
- Expanding the system to track multiple objects or people simultaneously.
