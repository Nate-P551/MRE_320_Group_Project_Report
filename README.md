# MRE_320_Group_Project_Report

By: Nathan Price and Zhiuri Sun
Fall 2022 MRE 320 Sensors and Actuators

# Intro
Attached should be the folders containing the code used to run our Jetbot for our group project
where we had to follow a track in a race, both when manually controlling the Jetbot and when 
having it follow the track itself.

# Basic Motion
We first initially used this folder of code to initially test our overall setup, making sure there was 
a stable connection between our computer and the Jetbot, as well as understanding the general motion of
the Jetbot and how to expect it to move for the rest of the project

# Manual Control
In order to manually control the Jetbot, we implemented the code in the teleoperations folder 
which allowed us to use an xbox controller to control each motor individually to make our way through the track.

# Automatic Mode
In order to have the Jetbot automatically move down the track, we implemented the code in the road_following
folder. We first had to run a separate set of programming within the folder to first collect data on the track 
itself by taking around 200-300 pictures of the track using the camera on our Jetbot and marking the point we wanted 
the Jetbot to proceed towards if it saw that position. Then we had to run another set of programming to take that 
data and use it to train the Jetbot on an acceptable path. The last major section of code started the Jetbot and allowed 
for us to change the speed and overall turning speed of the Jetbot to optimize its learned path around the track.
