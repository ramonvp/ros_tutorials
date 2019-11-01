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

# Tutorial 9
Checking rosed to directly edit files faster.
I had to install vim with:
``` sudo apt install vim ```

Since vim is a bit difficult to understand all the keyboard commands, I changed my default to editor to nano, which I know better. This can be done adding the following line in your .bashrc user home directory:
``` export EDITOR='nano -w' ```

# Tutorial 11
After following the steps described in the tutorial, I run the nodes with these commands in separate shells:
```
rosrun begginer_tutorials talker
rosrun begginer_tutorials listener
```
And I can observe in the talker window:
```
...
[ INFO] [1572607668.634235135]: hello world 180
[ INFO] [1572607668.734235464]: hello world 181
[ INFO] [1572607668.834269658]: hello world 182
[ INFO] [1572607668.934264650]: hello world 183
...
```
And in the listener window:
```
...
[ INFO] [1572607668.634506434]: I heard: [hello world 180]
[ INFO] [1572607668.734737405]: I heard: [hello world 181]
[ INFO] [1572607668.834739739]: I heard: [hello world 182]
[ INFO] [1572607668.934757512]: I heard: [hello world 183]
....
```
