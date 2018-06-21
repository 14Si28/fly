## Intro to vehicle control

In the case of a flying vehicle to reach to a certain altitude, if we apply some thrust (say in proportion to the altitude), it will start accelearating
in z direction and overshoots the target altitude, and if we want to come back to the same altitude we have to again 
go down and up and start occilating around the point to reach there.

To avaiod this process of occilation, we need PID controller where P, I and D stands for Proportional, Integration and differenciation.

(looks like we have to apply thrust based on the altitude remaining after continiuous integration and differentiation)
