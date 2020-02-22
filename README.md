# Install Catkin Prebuilt Package
```sh
$ sudo apt-get install ros-melodic-catkin
```

# Creating a workspace for catkin

```sh
$ source /opt/ros/melodic/setup.bash
```

[Catkin workspace layout:] (http://wiki.ros.org/catkin/workspaces)

```sh
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```

```sh
$ source devel/setup.bash
$ echo $ROS_PACKAGE_PATH
/home/youruser/catkin_ws/src:/opt/ros/kinetic/share
```

# Build Packages
```sh 
$ cd ~/catkin_ws/src
$ git clone git@github.com:troshenkov/odrive_cpp_ros.git
cd ~/catkin_ws/
$ catkin_make
$ catkin_make install
```

