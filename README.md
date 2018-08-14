# LibMotor

Designed to abstract motor control with an arduino. Should be used with an H-Bridge (tested with an L298N).

Two classes are provided:

MDrive requires two digital pins, which are the control pins for the H-Bridge

WheelDrive requires an additional two digital pins, which should provide signals from an encoder. 
