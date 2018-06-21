## Intro to sensors docs 

#### Lesson Goals

* Combine measurements from different sensors.
* Derive measurement models
* Sensor calibration and initialization
 
#### Complementry sensors
There could be a question arise as "Why and what is the need of many sensors"? when we can do thing
with only a few sensors.
And the perfect answer to this question could be :

Many sensors are complementory to each other, for example accelerometer and GPS are complementry to each other.
Using only accelerometer could lead to more loss and error over time based on the initial velocity capture error,
where as GPS will alway have some error in its measurement but it doesn't grow over time.

Hence finding a perfect positon could be deduced from the fusion of readings of accelerometer and GPS.


## GPS

#### How GPS works?
GPS needs 4 satelites to position somebody at earth.
All the satelites uses time to receive signal from a body on earth and try to draw a circle where that body could exits
based on the time taken to receive the signal from the body (using speed of light, we can calculate the displacement).
Now, the same process is repeated with other 2 satelites and the interesection of possible circle of position of body 
is calculated (there could only be 2 points possible for 2 circles intersectiong). Now based on the 2 points found based on 
the intersection of cirecles drawn where the body could exits we can select only that point which is near to earth or 
not closer to the salelites. The other point will exits in the space.

The fourth saltelite is used for correcting the error in the measurement.

## Barometer
Barometer is used to measure altitude. Barometer actually measure atmoshpheric pressure and with that it calulates
the altitude of the vehicle.

## Summery
Sensor problem is not yet solved completely specifically in case of autonomous flights.
Mordern vehicles can use LIDAR,RADAR and many more advanced cameras for the flights.
This problem needs more attention before we increase the number of vahincles in the sky to be more precised over 
the accuracy of the measurement and positions.
