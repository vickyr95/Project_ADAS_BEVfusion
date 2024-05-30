# Project_ADAS_BEVfusion

**About**

[BEVFusion](https://github.com/mit-han-lab/bevfusion) is a research project from an MIT lab, presenting an efficient and versatile multi-task, multi-sensor fusion framework. It integrates multi-modal features (such as inputs from multiple cameras, LiDARs, and radar sensors) into a unified bird's-eye view (BEV) representation space, effectively preserving both geometric and semantic information.

Our client sought to implement this framework in their project, along with some additional features.

**Our Work**

For our client, we tested this framework using a custom dataset provided by them. We also converted the model's output into ROS-compatible data, enabling visualization in RViz according to their specifications. 

Concurrently, we trained lane-detection models ([CLRNet](https://github.com/Turoad/CLRNet) and [LaneDet](https://github.com/Turoad/lanedet)) to identify lane markers, and visualized these in RViz alongside data from BEVFusion. 

Initially, our work involved integrating Autoware and BEVFusion, but we later focused solely on using BEVFusion with ROS in response to the client's requirements.

The demo includes snapshots of our visualizations. The source code has been submitted to the client and cannot be published here as per their request.

**Takeaways**

- Gained insights into Autoware, multicamera, and sensor fusion technology, and their applications in Advanced Driver Assistance Systems (ADAS).
- Refreshed our skills in ROS2 through this project.

![BEV-ROS-demo](https://github.com/vickyr95/Project_ADAS_BEVfusion/blob/main/BEV-ROS-demo.gif)
