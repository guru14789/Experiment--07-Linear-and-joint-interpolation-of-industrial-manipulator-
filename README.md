# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### AIM :To understand linear and joint interpolation of industrial manipulator and develop a program for the same 


### NAME : SREEKUMAR S
### REGISTER NUMBER : 212223240157
### DATE : 22-04-2024
### DEPT : AIML
      
### EQUIPMENT REQUIRED : 

       Instrial manipulator , teach pendant and associated program platform 
      
### THEORY : 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### JOINT INTERPOLATION: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### STRAIGHT LINE INTERPOLATION : 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### CIRCULAR INTERPOPLATION : 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### MANUAL LEAD THROUGH PROGRAMMING : 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.


### Figure -01 difference between P-P , joint and linear interpolation 


![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)



### Program : 





![WhatsApp Image 2024-04-15 at 14 31 09_48a12f09](https://github.com/Beatricethomas/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/140035214/890b4c6b-1c09-46e6-af14-28fa76bbe89e)










### Robot movements 




![WhatsApp Image 2024-04-15 at 14 31 10_4a9aee90](https://github.com/Beatricethomas/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/140035214/9f64f40e-62fc-494f-8129-13ddb3f9cd14)





![WhatsApp Image 2024-04-15 at 14 31 10_26f08ac6](https://github.com/Beatricethomas/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/140035214/258565ed-c9e4-463e-8ed8-3f2baeaf9468)





### Results:  

Thus, the linear and joint interpolation of industrial manipulator is executed with a suitable
program.
