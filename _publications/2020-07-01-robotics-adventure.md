---
title: "Robotics Adventure"
permalink: /publication/2020-07-01-robotics-adventure
paperurl: 'https://github.com/sldai/RoboticsAdventure'
---

This projects contains my robotics knowledge and common robotics algorithm demo.

![Knowledge graph](http://sldai.github.io/images/Robotics_Adventure/knowledge_graph.png)


---------------------------------

## Perception

Edge features
--------------------

![canny](https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Perception/Vision/figure/canny.png)

Key point features
-----------------------

![harris](https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Perception/Vision/figure/corner_detection.png)


ORB SLAM
---------

<iframe width="868" height="488" src="https://www.youtube.com/embed/GWl_Ffzc6oo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


-------------------------------------------------------------------


## Planning

Deterministic Search
--------------------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/dijkstra.png" alt="dijkstra"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/astar.png" alt="A*"></td>
  </tr>
    <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/dstar.gif" alt="D*"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/anytime_dstar.gif" alt="Anytime D*"></td>
  </tr>
</tbody>
</table>

Stochastic Search
--------------------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/rrt.gif" alt="RRT"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/rrt_connect.gif" alt="RRT Connect"></td>
  </tr>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/rrtstar.gif" alt="RRT*"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/dynamic_rrt.gif" alt="Dynamic RRT"></td>
  </tr>
    <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/bitstar.gif" alt="BIT*"></td>

  </tr>
</tbody>
</table>

RL RRT
------
<iframe width="868" height="488" src="https://www.youtube.com/embed/FtSNSGTWECs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Spline Curve
----------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/cubic_spline_2D.png" alt="cubic_spline"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/bezier_curve.png" alt="bezier_curve"></td>
  </tr>
</tbody>
</table>

<!-- Polynomail Trajectory
--------------------- -->
<!--
<table>
<tbody>
  <tr>
    <td><img src="figure/cubic_polynomial.gif" alt="cubic_polynomial"></td>
    <td><img src="figure/quintic_polynomial.gif" alt="quintic_polynomial"></td>
  </tr>
</tbody>
</table> -->

Dubins/Reeds Shepp Curve
----------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/dubins_curve.png" alt="dubins_curve"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/rs_curve.png" alt="rs_curve"></td>
  </tr>
</tbody>
</table>


Dynamic Window Approach
-----------------------

![dwa](https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Planning/figure/dwa.gif)


--------------------------------------------------


## Control

Two link arm
-------------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/Setpoint_PID.gif"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/Setpoint_PID_with_IK.gif"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/PID_path_tracking.gif"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/PID_path_tracking_with_IK.gif"></td>
  </tr>
</tbody>
</table>

Car
---------

<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/pp.gif"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/frontwheel.gif"></td>
  </tr>
</tbody>
</table>
<table>
<tbody>
  <tr>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/rearwheel.gif"></td>
    <td><img src="https://raw.githubusercontent.com/sldai/RoboticsAdventure/master/Control/figure/lqr_kinematic.gif"></td>
  </tr>
</tbody>
</table>

--------------------------------------------------