## Real world planning

In the real world, nothing is static and hence we need more better planning than assumed.
In most of the cases we assume our position and obstacles static but in the real world obstacle may come anytime,
GPS has inbuit variance which will give you error in most of the cases. 

In these kind of senarios we need a robust plannign for autonomus ariel vehicles.

In most of the cases, we assume as long as there is straight line available between 2 points, that path can be
traced by the arial vehicle. But in real world, there are kinematic constraints, constraints due to mass and foces
acting on the body. Say for example there is always a constraint on a body due to its mass as how much it can be
accelarated and what could be the max velocity, how fast it can move to the other direction on some rotation angle.
