# Ackermann Steering Control
[![Build Status](https://travis-ci.com/govindak-umd/Ackermann_Steering_Controller.svg?branch=master)](https://travis-ci.com/govindak-umd/Ackermann_Steering_Controller)
[![Coverage Status](https://coveralls.io/repos/github/govindak-umd/Ackermann_Steering_Controller/badge.svg?branch=master)](https://coveralls.io/github/govindak-umd/Ackermann_Steering_Controller?branch=master)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
---

## Authors

Sprint 1:
- Driver : Govind Ajithkumar
- Navigator : Pradeep Gopal
- Design Keeper : Justin Albrecht

Sprint 2:
 - Part 1 - Implementation of the code : 
     * Driver : Justin Albrecht
     * Navigator : Govind Ajithkumar
     * Design Keeper : Pradeep Gopal
 - Part 2 - Testing and code quality check : 
     * Driver : Pradeep Gopal
     * Navigator : Justin Albrecht
     * Design Keeper : Govind Ajithkumar

## Overview
For this project we are going to implement a controller that uses the Ackermann kinematic steering equations for the Acme Robotics company. The Ackermann equations assume that a four wheeled vehicle travels around an instantaneous center of curvature and can compute the kinematics for given turning angles for both the inner and outer wheels. The basic idea behind Ackermann steering is that the inner wheel should steer for a bigger angle when compared to the outer wheel. This stops the wheels from slipping side ways when the vehicle follows a curved path. We are assuming that the controller is for a four wheeled robot with front-wheel steering and rear-wheel drive. 

The following assumptions are made while developing this project :-
 1. All vehicle parameters are known.
 2. The initial position, orientation and velocity of the vehicle are taken as user inputs.
 3. Desired position, orientation and velocity of the vehicle are given by user. 
 4. Friction, Wheel slippage and actuator saturation is minimal.
 5. The initial velocity is set to be zero i.e v = 0.
 6. The maximum steering angle is 45 degrees.
 
 ## Agile Iterative Process (AIP)
This project was completed using AIP with the involvement of 3 programmers using Pair-programming in turns. The detailed Product Backlog, Iteration Backlogs and Work Log are mentioned in the link given below : 
https://docs.google.com/spreadsheets/d/1mllm-lFvLnS9uENkift7FDs6RVxYKf9B1DdrZmD5e4E/edit?usp=sharing

## Google Doc Link for Sprint Planning and notes
https://docs.google.com/document/d/1MYrVPlC8CS4HKTRGY48tLDCI4FuRGh4HkhqQqH0sPOc/edit?usp=sharing

<p align="center">
  <img width="250" height="250" src="https://github.com/Pradeep-Gopal/Temp/blob/main/images/ackermann_steering.jpeg">
  <img width="250" height="250" src="https://github.com/Pradeep-Gopal/Temp/blob/main/images/controller_block_diagram.jpeg">
</p>


