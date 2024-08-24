
# Reactive Navigation - Mars Rover Prototype

This project was implemented at the GUJCOST RoboFest 3.0, a national competition, where our team won the prize money of 10 lakh rupees. We were awarded the best autonomous functioning rover. My role in the team was to write the autonomous algorithm.

## Overview

This project involves the development of an autonomous 4-wheel differential drive Mars Rover prototype designed for traversal in unknown Martian terrain. The rover was equipped with various sensors and technologies to achieve robust obstacle avoidance and efficient goal-to-goal traversal.

## Key Features

- **Autonomous Navigation**: Developed a reactive navigation algorithm for the Mars Rover to traverse unknown and unpredictable Martian terrain effectively.
- **Obstacle Avoidance**: Programmed the rover to detect and avoid obstacles using a combination of LiDAR, GPS, and IMU data.
- **Goal-to-Goal Traversal**: Implemented algorithms for the rover to autonomously move from one specified location to another using GPS coordinates.
- **Sensor Integration**: Used LiDAR to create a cloud map of the surroundings, which was processed for real-time decision-making.
- **Microcontroller and SBC Integration**: Successfully integrated microcontrollers like ESP32 and Arduino Mega, and single-board computers like Raspberry Pi and Jetson Nano into the ROS framework for seamless operation.

## Technologies Used

- **Languages**: Python
- **Frameworks/Tools**: ROS (Robot Operating System), Gazebo (for simulation)
- **Hardware**: ESP32, Arduino Mega, Raspberry Pi, Jetson Nano
- **Sensors**: LiDAR, GPS, IMU

## Project Achievements

- **National Competition Winner**: Secured first place in the GUJCOST RoboFest 3.0, winning a prize of 10 lakh rupees.
- **Best Autonomous Functioning Rover**: Awarded for having the best autonomous functioning rover among all participants.
- **Role and Contribution**: As part of the team, my main contribution was in writing the autonomous navigation algorithm that ensured the rover's ability to handle various terrain challenges and navigate effectively.

## How to Run the Project

1. **Set Up the Hardware**: Assemble the Mars Rover with the required microcontrollers, sensors, and single-board computers.
2. **Install ROS and Dependencies**: Ensure that ROS is installed on the single-board computers. Install necessary Python packages and ROS dependencies.
3. **Launch the Rover**: Use the following command to start the rover's navigation system:

    ```bash
    rosrun $(your_package_name) hardware_auto2.py
    ```

4. **Monitor and Control**: Use RViz or other ROS-compatible visualization tools to monitor the rover's real-time navigation and obstacle avoidance.

## Future Work

- **Enhancing Terrain Mapping**: Incorporating more sophisticated mapping algorithms for better terrain analysis and obstacle detection.
- **Advanced Localization**: Implementing SLAM (Simultaneous Localization and Mapping) for improved localization accuracy in dynamic environments.
- **Autonomous Path Planning**: Developing more advanced path planning algorithms to handle complex terrain and optimize route efficiency.

## Conclusion

This project lays a solid foundation for autonomous exploration in challenging terrains like those found on Mars. The combination of robust hardware, efficient algorithms, and real-time data processing demonstrates the potential for future advancements in autonomous navigation technology.
