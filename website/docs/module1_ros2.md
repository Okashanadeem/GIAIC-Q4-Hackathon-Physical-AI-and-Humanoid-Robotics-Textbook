# Module 1: The Robotic Nervous System (ROS 2)

## Focus: Middleware for Robot Control

This module introduces students to the Robot Operating System (ROS 2), a flexible framework for writing robot software. ROS 2 provides a standardized way for different software components to communicate and coordinate within a robotic system. It acts as the "nervous system" of a robot, enabling robust and distributed control.

## Key Concepts

### ROS 2 Nodes, Topics, and Services

*   **Nodes**: Individual processes that perform computation (e.g., a node for reading sensor data, a node for controlling motors).
*   **Topics**: A publish/subscribe communication mechanism where nodes publish data to topics, and other nodes subscribe to those topics to receive data.
*   **Services**: A request/reply communication mechanism used for synchronous operations where a client node sends a request to a service server, and the server processes it and returns a response.

### Bridging Python Agents to ROS Controllers using `rclpy`

`rclpy` is the Python client library for ROS 2. It allows developers to write ROS 2 nodes in Python, enabling seamless integration between high-level AI agents (potentially written in Python) and low-level robot controllers.

### Understanding URDF (Unified Robot Description Format) for Humanoids

URDF is an XML format used in ROS to describe the kinematic and dynamic properties of a robot. For humanoid robots, URDF defines:

*   **Links**: The rigid bodies of the robot (e.g., torso, head, limbs).
*   **Joints**: The connections between links, specifying their type (revolute, prismatic) and limits.
*   **Visual and Collision Properties**: How the robot looks and its physical interaction properties for simulation.

## Weekly Breakdown (Weeks 3-5: ROS 2 Fundamentals)

*   ROS 2 architecture and core concepts
*   Nodes, topics, services, and actions
*   Building ROS 2 packages with Python
*   Launch files and parameter management
