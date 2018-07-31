Group member: James Feng, Andrew Lin, Hao Zhang

Concepts of Localization for Autonomous Driving
With the increasing availability and decreasing costs of advanced input and output technology, there has been a growing interest from the automotive industry to develop autonomous vehicles. Global positioning system (GPS) technologies have advanced significantly in the past decade. Modern day smartphones are currently accurate down to 4.9 meters, while higher end dual frequency receivers are accurate down to a few centimeters. However, with environmental factors, such as trees, buildings and tunnels, these systems cannot be the sole technology to predict location. Furthermore, the behavior of other vehicle operators requires sensor technologies that can detect and respond to their environment. As a result, advanced imaging technologies, including LIDAR, sonar, radar, stereoscopic imaging, etc., have been proposed as a solution to this problem. Similar to GPS’s, these technologies also suffer from limitations of inaccuracy. It is therefore unavoidable to depend on software tools to account for inaccuracies and lack of precision in modern day sensors.

We therefore propose to develop a simplified localization program. Users will input a variety of variables (2-D environment array, measurements, motions, sensor accuracy, and motor output accuracy), to create a 2-D array of localization probabilities.


Inputs:
--2-D Array of environment - 2D array, each entry either 'R' (for red cell) or 'G' (for green cell)
--Sensor Measurements – List of measurements recorded by the vehicle, with each entry reporting a 'R' or 'G'
--Motions – List of actions taken by the robot, with each movement being dictated in the form of an x, y coordinate
--Sensor accuracy – Accuracy of the sensor in detecting the correct color
--Movement accuracy – Probability that a movement actually occurred


Outputs:
The function should print a 2D list (of the same dimensions as the “2-D Array of environment”) that gives the probabilities that the robot occupies each cell in the world.


Anticipate Requirements:
--Bayesian Probability
--For loops
--Boolean Logic
--If/else
--Lists
