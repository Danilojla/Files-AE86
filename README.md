# Files-AE86



1.Building documentation
2.The car
  a.Movement
     i.  Motors
    ii.  Chassis
    iii. Transmission
    iV.  Drive
  b.Power
  c.Sense
    i. Sensors
    ii. Camera
  d.Obstacle management
      i. Decision making




AE86

Movement

Chassis
For the chassis, we used one from an RC car based on the AE86 model. We mostly chose that one because it resembles the car from our 
mentor, but it also has ample space for the electronics and motors, making it a suitable chassis. The upper part is easy to take 
off, allowing for fast and simple modifications or fixes to take place.

Motor
The motors we used are the INJORA RC 050 50T Pro brushed motor. This motor is the one responsible for propelling the car forward. The RPM, 
voltage and power is excellent for its size.

Then we have the EPINON Emax Servo ES08MAll. This is the one that allows the car to swerve left and right with great precision. It also 
happens that the EPINON is the one that semi-professional RC cars use, showing how good it is.

Gear Box
Our GearBox is the WOAEIOUS, we chose it because it is the same one the Ford Bronco 1/24 uses.


 

Main Axle (AWD)
We are using the HOPLEX RXtransmission axis, these are connected to the INJORA 1/24 axle.

Power

We have the (name) driver, it has a 200mA regulator, 2 outputs for 12V and 5V respectively, and 1 input for 12V

The whole circuitry is connected like so:




Main Controller 
We have the Arduino NANO Elegoo, we chose it mostly because of its size, since our car is smaller than usual, fitting a normal sized Arduino
would have proved to be a challenge.



Battery
We used a 12V nickel battery

Sense

Sensors
We have 2 Comimark GP2Y0A21YKF that work as our distance sensor, they work with a combination of PSD, IRED and circuit processing signal. They 
let the robot know where things are relative to him.



Camera
We have the HUSKYLENS as our color detecting sensor. We use the HUSKYLENS over other sensors or cameras because it has a built-in AI that we can
"program" on the camera itself. This makes it easier for us to calibrate the colors of the objects it has to dodge. It also has a bigger field
of view than usual sensors.

Decision making

The car detects with the HUSKYLENS the pillar in the circuit, and depending on the color, it drifts left or right. It tries to maintain itself on 
the middle by calculating said middle with the sensors, this is possible thanks to our PD controller on the programmation.





