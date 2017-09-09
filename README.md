# Aerial-Robotics
[//]: # (Image References)

[image1]:./Images/Project%201/1-D_Quadrotor.jpg
[image2]:./Images/Project%202/quad.jpg

This respoitory contains projects done in the  Aerial Robotics course part of the Robotics Specailization at Coursera. The course was  taught by Prof Vijay Kumar at UPenn. This respotiry is meant to share the results of the projects done and their implementation.

_**Orignal source code is provided and licensed by Coursera Robotics Specailization. Please do not plagarize if you are a student of the course as that would violate the Coursera Honor Code. My only contribution here is filling the skeleton source code to complete the needed tasks & objectives in the Projects.**_

### For more information on the course :

 * Coursera Page for [Robotics specialization](https://www.coursera.org/specializations/robotics) 
 * Coursera Page for [Aerial Robotics](https://www.coursera.org/learn/robotics-flight) 
 
## Programming Project 1 - PD Control of Quadrator height in 1-D

__**Objective :**__ The goal of  this exercise is  to implement a PD controller to control the height of a quadrotor, as well
as tune its gains. The controller only contains a Proportional and Derivate gain. In addition the input should
have a rise time of less than 1s and a maximum overshoot of less than 5%.
                                          
 <p align="center"><img src="./Images/Project%201/1-D_Quadrotor.jpg" /></p>

__**Dynamics of a Quadrotor in 1-D :**__

![equation](http://latex.codecogs.com/gif.latex?U_t%3D%5Ctext%20%7B%20Control%20Input%20at%20time%20%7D%20t)
![equation](http://latex.codecogs.com/gif.latex?P%28s%20%7C%20O_t%20%29%3D%5Ctext%20%7B%20Probability%20of%20a%20sensor%20reading%20value%20when%20sleep%20onset%20is%20observed%20at%20a%20time%20bin%20%7D%20t)

__**Results Obtained :**__

 <p align="center"><img src="./Images/Project%201/pdcontrol_1d.gif" /></p>


## Programming Project 2 - PD Control of Quadrator in 2-D Plane 

__**Objective :**__ The goal of  this exercise is  to implement a PD controller to control the motion of a quadrotor in 2-D plane , as well as tune its gains. The controller only contains a Proportional and Derivate gain. In addition the input should
have a rise time of less than 1s and a maximum overshoot of less than 5%.

 <p align="center"><img src="./Images/Project%202/quad.jpg" /></p>
