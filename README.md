# ros_tutorials
Homework exercise 1.3 for Integration in Master in Robotics, UVic

# Tutorial 5
Here is the output of the turtlesim:

![Turtle sim](media/turtlesim.png)

# Tutorial 6

Some sample screenshots I got doing tutorial 6:

![rqt_graph initial](media/rqt_graph.png)


![rqt_graph final](media/rqt_graph2.png)

# Tutorial 7
Calling services:
```rosservice call /spawn 2 2 0.2 "" ```
![call spawn service](media/t6_service_spawn.png)

Changing parameters:
```
rosparam set /background_r 0
rosparam set /background_g 255
rosparam set /background_b 0
rosservice call /clear
```
![setting green background](media/t6_param.png)

# Tutorial 8
Setting the log level of the console:
![rqt_console](media/t8_rqt_console.png)

Launching a roslaunch file:
![launching launch file](media/t8_roslaunch.png)

Using rqt tools, rqt_graph in this case:
![rqt_graph with dual sim](media/t8_rqt_graph.png)
