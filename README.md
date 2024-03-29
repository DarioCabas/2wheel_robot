[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->

<br />
<p align="center">
  <a href="https://github.com/DarioCabas/ROS_Webpage">
    <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo" width="80" height="80">
  </a>
</p>

# TWO WHEEL ROBOT IN GAZEBO-ROS

_This is a short description about the content of my proyect. In this project I create a robot with ROS, we use a URDF model to construct our robot and uses the xacro files for more structure code of the robot in a different files. So in this present project you can see a robot based in two wheels and a caster front that can visualize en RVIZ that is a tool for visualization._


## Getting Started🚀


_These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See_ **_Deployment_** _for notes on how to deploy the project ._


## Prerequisites:clipboard:

_You need to install all packages of_ **_ROS Melodic_** _and in the same way you need to use the_ **_RVIZ_** _if you want to see the model of your robot how its going on, and for the last_ **_Gazebo_** _permit to control the robot, I use this robot in another repository that you can find in the next link:_


https://github.com/DarioCabas/ROS_Webpage


### Installing🔧

#### Clone

- _Clone this repo to your local machine using_ `https://github.com/DarioCabas/2wheel_robot`

- _You can find the robot in the file named 2wheel_robot_

#### Setup

- _Make sure git is installed on your Ubuntu machine:_

```
  sudo apt-get install git
```

- _Download the source code from the gazebo_ros_pkgs github repository:_

```
  cd ~/catkin_ws/src
  git clone https://github.com/ros-simulation/gazebo_ros_pkgs.git -b melodic-devel
```
- _Check for any missing dependencies using rosdep:_

```
rosdep update
rosdep check --from-paths . --melodic-src --rosdistro melodic
```
- _You can automatically install the missing dependencies using rosdep via debian install:_

```
  rosdep install --from-paths . --ignore-src --rosdistro melodic -y
```
- _To build the Gazebo ROS integration packages, run the following commands:_

```
  cd ~/catkin_ws/
  catkin_make
```

## Running the tests ⚙️

**Running the model with RVIZ**

![Recordit GIF](http://g.recordit.co/2arPhSURiX.gif)

Model in RVIZ

<p align="center">
  <img width="600" height="400" src="https://i.imgur.com/nII5IIi.gif" >
</p>

**Run model into Gazebo**

![Recordit GIF](http://g.recordit.co/FRvSf98Xin.gif)

**Teleoperation of the robot**

![](2wheel_robot_1/img/teleop.gif)

## Deployment📦

_For use the teleoperation keyboard you need to download the teleop_twist_keyboard from the github to your ~/catkin_ws/src folder. Steps :_

```
  cd ~/catkin_ws/src
```
```
  git clone https://github.com/ros-teleop/teleop_twist_keyboard
```
```
  cd ~/catkin_ws
```
```
  catkin_make
```
```
  source ~/catkin_ws/devel/setup.bash
```
```
  source ~/.bashrc
```

_You have your ros environment in your bashrc file. If you don't have do the next steps:_

```
  gedit ~/.bashrc
```
```
  source ~/catkin_ws/devel/setup.bash
```

## Built With🛠️

* [ROS Melodic Morenia](http://wiki.ros.org/melodic) - The robot framework used
* [RVIZ](http://wiki.ros.org/rviz) - 3D visualizer for the Robot Operating System (ROS) framework
* [Gazebo](http://gazebosim.org/tutorials?tut=ros_overview) - Simulator

## Authors✒️

* **Dario Cabascango** - *Initial work* - [2wheel_robot](https://github.com/DarioCabas)

## License📄

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**


## Contact:e-mail: 

#### Feel free to contact me!

_Dario Cabascango_  - _hz-hertzio@hotmail.com_ 

_Project Link:_ _[https://github.com/DarioCabas/2wheel_robot](https://github.com/DarioCabas/2wheel_robot)_


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/DarioCabas/2wheel_robot.svg?style=flat-square
[contributors-url]: https://github.com/DarioCabas/2wheel_robot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/DarioCabas/2wheel_robot.svg?style=flat-square
[forks-url]: https://github.com/DarioCabas/2wheel_robot/network/members
[stars-shield]: https://img.shields.io/github/stars/DarioCabas/2wheel_robot.svg?style=flat-square
[stars-url]: https://github.com/DarioCabas/2wheel_robot/stargazers
[issues-shield]: https://img.shields.io/github/issues/DarioCabas/2wheel_robot.svg?style=flat-square
[issues-url]: https://github.com/DarioCabas/2wheel_robot/issues
[license-shield]: https://img.shields.io/github/license/DarioCabas/2wheel_robot.svg?style=flat-square
[license-url]: https://github.com/DarioCabas/2wheel_robot/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/dario-cabascango-9724431a3


