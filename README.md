# Monte_Carlo_Localisation MCL

The MCL algorithm was exploited using a mobile robot. The theoritical reference about the concept can be obtained from the following:

References : " Probabilistic Robotics" by Wolfram Burgard, Sebastian Thrun, Dieter Fox

Scenario : In this task , a mobile robot represented with a blue color circle occupies the space in a 2D map of size 100 by 100.The robot has the ability to manoeuvre in x , y & theta respectively. The range finder sensors present in the robot can measure the robot distance from its landmarks. Each landmark was represnted with the red color. 

The following would be the break of the MCL approach :

1. Motion and Sensing – Moving the robot and measuring the distance to the landmarks.
2. Noise              – Simulate the noise and add to the measurements.
3. Particle Filters   – Randomly and uniformly spread the particles through out the map.
4. Importance Weight  – Evaluate the importance weight of each particle.
5. Re-sampling        – Re-sample the particles.
6. Error              – Generate the error value to check the overall quality of the solution. By this step , we get to know how close the particles are to the       robot.
7. Graphing           – Plot the position of robot and particles at each iteration of the MCL algorithm.
