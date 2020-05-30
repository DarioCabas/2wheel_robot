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
    <img src="https://imageog.flaticon.com/icons/png/512/25/25231.png?size=1200x630f&pad=10,10,10,10&ext=png&bg=FFFFFFFF" alt="Logo" width="150" height="80"
  </a>
</p>

# TWO WHEEL ROBOT IN GAZEBO-ROS

_This is a short description about the content of my proyect. In this project I create an interface using a web page trough  HyperText Markup Language (HTML) and using some basic communication between the page and the robot that I made in RVIZ that is a 3D visualization tool for ROS. The objetive is control a two wheeled robot with the page web interface._

## Table of contents
* [Getting Started](#Getting-Started)
* [Prerequisites](#Prerequisites)
  * [Installing](#Installing)
* [Running the tests](#running-the-tests)
* [Deployment](#deployment)
* [Built With](#built-With)
* [Authors](#authors)
* [License](#license)
* [Contact](#contact)



## Getting Started🚀


_These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See_ **_Deployment_** _for notes on how to deploy the project ._


## Prerequisites:clipboard:

_You need to install all packages of_ **_ROS Melodic_** _and in the same way you need to use the_ **_Rosbridge server_** _for enabled the communication so you need a mobile robot or in another case visit my another repository to use mine, you can find it in the next link:_


https://github.com/DarioCabas/2wheel_robot


### Installing🔧

#### Clone

- _Clone this repo to your local machine using_ `https://github.com/DarioCabas/ROS_Webpage`

#### Setup

- _Create a virtual environment for Python 3:_

```
  virtualenv venv --python=python3
  source venv/bin/activate
```

- _Run the webserver for static pages:_

```
  cd ROS_webpage
  python -m http.server
```
- _Run ROSBridge Websocket Server:_

```
roslaunch rosbridge_server rosbridge_websocket.launch
```

## Running the tests ⚙️

**Run Web Server**

![Recordit GIF](http://g.recordit.co/Bep26ht7lG.gif)

**Run Two Wheel Robot**

![Recordit GIF](http://g.recordit.co/x7LbwonQLx.gif)

**Interface with the robot**

![](https://im4.ezgif.com/tmp/ezgif-4-af25e940a0d7.gif)

## Deployment📦

_Don't forget to create a environment for python3 when you clone for the first time , because in that environment runs the web server, with the next command you can create:_

```
  virtualenv venv --python=python3
```
<p align="center">
  <img width="460" height="300" src="https://im4.ezgif.com/tmp/ezgif-4-c9215dd4f3e5.gif">
</p>

## Built With🛠️

* [ROS Melodic Morenia](http://wiki.ros.org/melodic) - The robot framework used
* [Bootstrap](https://getbootstrap.com/) - Template starter page
* [Vue.js](https://vuejs.org/) - Progressive JavaScript Framework 
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


