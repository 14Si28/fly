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
