## Extended Kalman filter
In estimation theory, the extended Kalman filter (EKF) is the nonlinear version of the Kalman filter which linearizes about an estimate of the current mean and covariance. In the case of well defined transition models, the EKF has been considered[1] the de facto standard in the theory of nonlinear state estimation, navigation systems and GPS.

## Disadvantages

Unlike its linear counterpart, the extended Kalman filter in general is not an optimal estimator (of course it is optimal if the measurement and the state transition model are both linear, as in that case the extended Kalman filter is identical to the regular one). In addition, if the initial estimate of the state is wrong, or if the process is modeled incorrectly, the filter may quickly diverge, owing to its linearization. Another problem with the extended Kalman filter is that the estimated covariance matrix tends to underestimate the true covariance matrix and therefore risks becoming inconsistent in the statistical sense without the addition of "stabilising noise" [8] .

Having stated this, the extended Kalman filter can give reasonable performance, and is arguably the de facto standard in navigation systems and GPS.

