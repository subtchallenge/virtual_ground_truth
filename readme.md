# README #

This repo provides point cloud data for the DARPA Subterranean Challenge Virtual Competition worlds. The tile meshes, as well as artifact and obstacle locations in each world, can be found on the [SubT Tech Repo](https://subtchallenge.world/openrobotics/fuel/collections/SubT%20Tech%20Repo).

### Files ###

* data/_worldname_.pcd -- Point cloud sampled from each virtual world mesh, defined in the DARPA Cartesian coordinate frame.

### Course Visualization in RViz ###

The world point clouds may be visualized as point clouds using ROS and RViz. This package depends on ROS and the `pcl_ros` package to build. 

To visualize the point clouds, run `roslaunch virtual_ground_truth view.launch`. Pass with the course argument, e.g., `course:=final_event_01` to visualize a particular course.

### Links ###

* Virtual Worlds -- [SubT Tech Repo](https://subtchallenge.world/openrobotics/fuel/collections/SubT%20Tech%20Repo) ("Worlds" tab)

### Contact Information ###

If you have any questions or comments about this repository, please contact:

* Angela Maio - angela.c.maio.civ@army.mil
* SubT Challenge Mailbox - SubTChallenge@darpa.mil
    
