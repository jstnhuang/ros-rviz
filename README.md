# \<ros-rviz\>
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/jstnhuang/ros-rviz)

A Polymer element for ROS visualization.
Version 1 is a hybrid element that supports Polymer 1 and Polymer 2.

- [Documentation](https://www.webcomponents.org/element/jstnhuang/ros-rviz/elements/ros-rviz)
- [Demo](https://www.webcomponents.org/element/jstnhuang/ros-rviz/demo/demo/index.html).
  Note that the demo requires a secure websocket server, since it is served over HTTPS.

To run the demo, run rosbridge, tf2_web_republisher, and the interactive marker proxy as needed.

Example:
```
roslaunch pr2_gazebo pr2_empty_world.launch
roslaunch rosbridge_server rosbridge_websocket.launch
rosrun tf2_web_republisher tf2_web_republisher
```

To run the tests, run the following:
```
roscore
roslaunch rosbridge_server rosbridge_websocket.launch
polymer test
```
