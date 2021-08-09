# Fire-Fighting-Robot
In this Project, I have Worked on a Robot which is used to extinguish fire automatically.

Material Required:
Arduino UNO
Fire sensor or Flame sensor (3 Nos)
Servo Motor (SG90)
L293D motor Driver module
Mini DC Submersible Pump
Small Breadboard
Robot chassis with motors (2) and wheels(2) (any type)
A small can
Connecting wires

In this project,I have three fire Sensor namely Left_Sensor,Right_sensor and Forward_sensor which is used to detect
the fire through infra red rays.  When fire burns it emits a small amount of Infra-red light, this light will be received by the IR receiver on the sensor module. Then we use an Op-Amp to check for change in voltage across the IR Receiver, so that if a fire is detected the output  pin (DO) will give 0V(LOW) and if the is no fire the output pin will be 5V(HIGH).
So, we place three such sensors in three directions of the robot to sense on which direction the fire is burning.
We detect the direction of the fire we can use the motors to move near the fire by driving our motors through the L293D module. When near a fire we have to extinguish it out using water. Using a small container we can carry water, a 5V pump is also placed in the container and the whole container is placed on top of a servo motor so that we can control the direction in which the water has to be sprayed.

