# ROS-Based Localization and Mapping Assignment

This repository contains the implementation for creating a 2D occupancy grid map using TurtleBot3.

## Features

- Wandering robot for autonomous navigation
- Real-time mapping and visualization in RViz
- Noise filtering and dynamic grid expansion
- Probabilistic mapping

## Repository Structure

- `src/`: Source code
  - `wandering_robot/`: Wandering robot implementation
  - `mapping/`: Mapping system implementations
- `support_docs/`: Supporting documents and screenshots
- `setup/`: Setup scripts

## How to Run

Follow these steps to run the project:

```bash
export TURTLEBOT3_MODEL=burger
roslaunch turtlebot3_gazebo turtlebot3_world.launch
rosrun rviz rviz
rosrun wandering_robot wandering_robot.py
rosrun mapping mapperv1.py
```
