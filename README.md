# Navigate_Multiple_Robots
打开gazebo的时候会发现一直处于黑屏这种状态，这是因为model库加载不正确导致的。
```
$ cd ~/.gazebo/
$ mkdir -p models
$ cd ~/.gazebo/models/
$ wget http://file.ncnynl.com/ros/gazebo_models.txt
$ wget -i gazebo_models.txt
$ ls model.tar.g* | xargs -n1 tar xzvf
```
如果还是黑屏 可以使用如下两条指令
```
killall gzserver
killall gzclient
```
![alt text](https://raw.githubusercontent.com/Pallav1299/Navigate_Multiple_Robots/master/thumbnail.png)

How to navigate multiple robots in simulation using ROS and Gazebo.

[![Watch the video](https://drive.google.com/file/d/14nKAhJnAltBh2-BE7m0fL__4v2HSFjEn/view?usp=sharing)](https://www.youtube.com/watch?v=iyL_hsqjKWI)

Topic Credits:
"The Construct"
