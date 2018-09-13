# This fork adds one feature: the stepper motor is powered off when it is finished rotating, to save about 60mA. This is useful for intermittent applications

# Arduino-and-ULN2003-Stepper-Motor-Driver
Using a ULN2003 Stepper Motor Driver with a 28BYJ-48 motor

These small motors are available cheaply on eBay and normally come with a ULN2003 driver board.
Unfortunatly they will not drive properly with the standard Arduino stepper motor library.
I looked at a number of solutions, but as all I wanted to do was to drive the servo motor to a fixed position
I have used the library included here. Download the library and rename  to StepperMotor
save to your library folder.

This library allows the number of steps, the direction of rotation and speed to be set.For more information see my blog at https://rydepier.wordpress.com/2016/03/31/uln2003-stepper-motor-driver-with-28byj-48-motor/
