# accelerometer-transformation
Build the rotation matrix to the accelerometer signals to transform smartphone's orientation relative to the car

# Problem Definition
Accelerometers are devices measuring proper accelerations, i.e. acceleration of a body in its own instantaneous rest frame (the coordinate system – frame of reference – in which the body is at rest).
When mounted on a car, such sensors are obviously directed towards the car motion (velocity vector),according to the reference axis shown in the left picture of Figure 1. Vice versa, having to rely on anexternal device, such as a mobile phone, we have no guarantee about accelerometer orientation.Figure 1. Reference axes for accelerometers mounted on a car (left picture) and available in a mobiledevice (right picture).
Suppose now that the smartphone is well fixed in the car in an unknown position; if the mobile reference frame is the one depicted in the right part of Figure 1, how we could efficiently and reliably transform the collected signals so as to match the reference frame on the left.

