# 2016-17-VEX-333X

This is the program I wrote for the 2017 VEX Robotics World Championship. 333x finished the season ranked 40th in the world, but were at one point ranked as high as 27th. At the start of the 2016-17 robotics season, I knew nothing about programming, and this final product demonstrates my growth from October 2016 to May 2017. I am mostly self-taught, scouring online resources such as https://www.vexforum.com/ to accrue knowledge. 

Special features of this program include: 
* An interactive LCD display to monitor sensor readings and battery levels, recalibrate sensors when necessary, and select autonomous variations
* 4 PID controllers running on separate tasks for the drive train, lift, and intake. The drive train used 3 sensors and had 2 separate PID controllers for driving straight and for turning
* Manual controls that override the PID controllers and set new targets
* A slew rate control on the drive train to minimize motor strain
* 5 Autonomous variations from each starting position to guarantee strategic advantage for every match
