# Home Service Robot #
#### Robotics Software Engineering ####
#### Term 2 ####
#### Project 5 ####

_Concepts/Skills Learned:_
  * Path Planning: discrete, sample-based, probabilistic
  * Minkowski sums
  * Configuration space, Voronoi diagrams, cell decomposition, potential fields
  * Searches: breadth-first, depth-first, uniform cost, A* 
  * A3C algorithm
  * Xterm Shell scripts

---

_Project Description:_

The last project in this term involved combining the previously-learned concepts of mapping and localization with automated movement. A custom robot model (from the Where Am I? project), titled Gorilla-bot, was used within a simple Gazebo environment. After successful integration with Rviz, the robot was tasked with successfully mapping its environment, using the graph-SLAM packages used in previous projects. This time, however, the robot was not controlled via keyboard inputs, but instead programmed with a rather simple "wall follower" node, which allowed for automated movement, keeping the robot near a wall at all times. 

Following successful automated mapping of its environment, the robot was tasked with a simulated "pick up and drop off" challenge. A point was picked on the map, with a visual marker appearing to designate an object of interest. Using the AMCL package and navigastion stack from previous projects, the robot was given capability to reach the desired destination on its own. Following this, a small application was added, which hid the object marker (simulating object pick-up), added a new point of navigation, and then made another identical object marker appear at said location once the robot successfully reached it (simulating object drop-off).

Although path-planning had been used extensively in previous projects, this project also provided lectures for a fundamental understanding, as well as common challenges, robotic path planning. This project also introduced the use of Xterm shell scripts to allow for more seamless integration of multiple active terminal windows.
     
   For a full report of how this was accomplished, see the included write-up: 
   
   [Home Service Robot Write-Up](https://github.com/akompaniyets/Home-Service-Robot/blob/master/Project%205%20Report%20.pdf)
