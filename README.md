# Tiago pick and place routine

The goal of the project is to implement a fetch and delivery behavior for the robot Tiago.
In the simulated environment there are two rooms separated by a wall, plus some obstacles into the environment.
In the first room is placed a table with some objects above that the robot has to fetch (red, blue and green),
plus gold hexagons that Tiago has to avoid, and thus not collide with them. Tiago has to grasp the correct
objects in some defined order, not collide to not wanted objects, move to the second room where are present
coloured tables, pick the color-associated table, move towards it, place the object and come back in the previous
room. The goal is considered achieved when Tiago places correctly the objects on the right tables in the wanted
order

<p align="center">
  <b>Pick</b><br>
  <img src="media_readme/pick.gif" width="45%" alt="Pick" />
  <b>Place</b><br>
  <img src="media_readme/place.gif" width="45%" alt="Place" />
</p>




## Files needed for execution
- [Environment and launch files](https://github.com/PieroSimonet/tiago_iaslab_simulation.git)
- [Apriltag](https://github.com/AprilRobotics/apriltag.git)
- [Apriltag_ros](https://github.com/AprilRobotics/apriltag_ros.git)
- [Gazebo_ros_link_attacher](https://github.com/pal-robotics/gazebo_ros_link_attacher.git)

## Commands to start simulation and pick and place procedure
To start the simulation:

> roslaunch assignment_2_group_12 Assignment2.launch

Launches the simulation with all action server nodes and service nodes.

PLEASE WAIT UNTIL TIAGO'S ARM IS TUCKED BEFORE LAUNCHING node_a!

>rosrun assignment_2_group_12 node_a

Starts the main node to begin the pick and place procedure

## Members
The project was developed with the collaboration of Stefano Trenti and Matteo Villani
