## SRF Robotics
The SRF Robotics GitHub page contains all of the code and documentation currently developed for the control and operation of the UR20 assembly system at Thomas Jefferson National Accelerator Facility. 

### System Components
The assembly system is composed of:
1. A UR20 from Universal Robots
2. A Robotiq Hand-E gripper
3. A Gocator 3520 snapshot camera

### System Framework
This system uses ROS 2 as the underlying framework for the control and component integration of the system. This is accomplished through custom bringup packages that integrated official packages with custom components. Additionally, 
this system uses the Flexible Behavior Engine (FlexBE) for high-level control, through Hierarchical Finite State Machines (HFSMs). This package leverages developed FlexBE states which provivde general control, with custom states and behaviors specifically for SRF development. 
