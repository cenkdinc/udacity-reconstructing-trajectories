# udacity-reconstructing-trajectories
Reconstruct a fairly complex vehicle trajectory by using time, displacement, yaw rate and acceleration data. Udacity - Intro to Self-Driving Cars - Chapter:8 - Lesson:4
# Working Algorithm
You need to define three basic functions to complete this project.
get_speeds(data_list): speed data is calculated by using time and acceleration data of the datalist. Discrete integration of acceleration gives speed.
get_headings(data_list): headings are calculated by using time and yaw rate data of the datalist. Discrete integration of yaw rate gives heading.
get_x_y(data_list): (x,y) tulips are calculated by using time, distance, and previously calculated headings with get_heading() function. Please note that trajectory is a list of tulips. Also, distance data gives the total distance traveled up to this point, not in each timestep.
# Testing Code
Next cells in the jupyter notebook contains testing codes.
# Derivative and Integration Algorithms.ipynb
This jupyter notebook contains simple codes for calculating the derivative and integration of continuous (analytical) functions and discrete real-world data.
