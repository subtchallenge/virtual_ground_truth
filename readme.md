# README #

This repo provides data for the DARPA Subterranean Challenge Virtual Competition worlds, including:

* ground truth data for Artifact types and locations

* point clouds sampled from the virtual world meshes

### Files ###

* Artifact_Ground_Truth.xlsx -- Spreadsheet listing each Artifact; its type; and x,y,z location in the relevant DARPA coordinate frame for each world.

* data/_worldname_.pcd -- Point cloud sampled from the virtual world mesh, defined in the DARPA Cartesian coordinate frame.

### Course Visualization in RViz ###

The world point clouds may be visualized as point clouds using ROS and RViz. This package depends on ROS and the `pcl_ros` package to build. 

To visualize the point clouds, run `roslaunch virtual_ground_truth view.launch`. Pass with the course argument, e.g., `course:=final_event_01` to visualize a particular course.

### Links ###

* Virtual Worlds
    * SubT Tech Repo ("Worlds" tab): https://subtchallenge.world/openrobotics/fuel/collections/SubT%20Tech%20Repo

### Contact Information ###

If you have any questions or comments about this repository, please contact:

* Ryan Halterman - ryhalt@spawar.navy.mil
* Angela Maio - angela.c.maio.civ@army.mil
* SubT Challenge Mailbox - SubTChallenge@darpa.mil
    
