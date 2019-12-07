# Where Am I?

In this project, you will learn to utilize ROS packages to accurately localize a mobile robot inside a provided map in the Gazebo and RViz simulation environments.

Over the course of the project, as part of the Robotics Software Engineer Nanodegree, you will learn about several aspects of robotics with a focus on ROS, including -

- Building a mobile robot for simulated tasks.

- Creating a ROS package that launches a custom r-obot model in a Gazebo world and utilizes packages like AMCL and the Navigation Stack.

- Exploring, adding, and tuning specific parameters corresponding to each package to achieve the best possible localization results.

## Installation Instructions

Some specific ROS packages might be required in order to complete the project -


``` bash
$ sudo apt-get install ros-kinetic-navigation
$ sudo apt-get install ros-kinetic-map-server
$ sudo apt-get install ros-kinetic-move-base
$ rospack profile
$ sudo apt-get install ros-kinetic-amcl
```

Once all the packages are installed, clone this repository to the src folder of your catkin workspace.


## Run the Project

You can launch it by running the following commands first -

```bash
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash
```

And then run the following in *separate* terminals -

``` bash
$ roslaunch my_robot world.launch
$ roslaunch my_robot amcl.launch

```


