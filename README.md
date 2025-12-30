# Beat Saber Dual-Arm Robot Controller

This project implements a real-time dual-arm task-space controller that allows
a humanoid robot to play a Beat Saber–style slicing game in simulation.

## Highlights
- Dual-arm IK with shared torso coordination
- Phase-based motion planning (approach → slice → recover)
- Continuous collision-based hit detection
- RViz-based visualization with custom markers

## Technical Details
- ROS 2 (rclpy)
- Jacobian-based task-space IK with damped least squares
- Nullspace optimization for posture, joint limits, and self-avoidance

## Demo
(Video / GIF here)

## Code Entry Point
`nodes/trajectory_node.py`
