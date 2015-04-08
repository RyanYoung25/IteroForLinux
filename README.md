ITERO: Linux Edition
=================================================

Itero: Latin, to repeat. 

Interactive Torso-tracking Enabling Robotic Operation, ITERO is a software system that allows users
regardless of their programming level to interact with and create movments for the humanoid robot HUBO. 
This is achived by using a Kinect sensor to monitor upper body motions of a person and mapping them to 
joint angle movements that HUBO can do. 

The original , ITERO, was developed by Matthew Wiese as advised by Ryan Young. 
The original project used a Kinect V2 which at the time required a windows 8 machine for the sdk which 
made it difficult to actually transmit data to a computer running MAESTOR. Matthew acheived this by 
using TCP sockets between the two computers to trasmit the data. The software worked very well and there 
is a demonstration video of it which you can find [here](https://youtu.be/X_c2yxpPKhs).

The problem with the original ITERO is that it required two computers on the same network to work. This became
burdensome so development of an ITERO system contained on one computer began. I took as much of the 
angle calculating math as I could from the orginal ITERO but I tried to rewrite it in a way that the software could
be expanded upon in the future. 

This can be done in simulation at home if you install the necessary dependencies below and run MAESTOR on your personal 
computer. We will be showing a live interactive demo at the Philly Tech Week Signature Event for 2015.

This is still under development and is not performing quite as well as the original ITERO yet.


Dependencies
============

This project will require a few dependencies:

- MAESTOR
- OpenNi ROS package
- OpenNi_tracker ros package
