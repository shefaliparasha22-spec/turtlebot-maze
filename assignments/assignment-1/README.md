# Assignment 1 - Getting Started with ROS

## Summary
This assignment covers setting up a ROS 2 development environment using Docker on Windows (via WSL2), and bringing up a TurtleBot3 simulation in a Gazebo maze world with RViz2 visualization.

## Environment
- Windows 11 with WSL2 (Ubuntu)
- Docker Engine (installed directly in WSL2, not Docker Desktop)
- VS Code with WSL and Docker extensions

## Steps Completed
1. Installed WSL2 and Ubuntu
2. Installed Docker Engine inside the WSL2 Ubuntu environment
3. Connected VS Code to the WSL2 environment
4. Cloned the turtlebot-maze repository
5. Built the Docker images using `docker compose build demo-world`
6. Launched the simulation using `docker compose up demo-world`
7. Verified the TurtleBot spawned correctly in Gazebo and RViz2

## Screenshots
- `command.png` - Terminal output showing ROS CLI commands and container startup logs
- `Gazebo.png` - Gazebo simulation showing the TurtleBot in the maze world
- `RVIZ.png` - RViz2 showing the robot's map, laser scan, and active navigation
