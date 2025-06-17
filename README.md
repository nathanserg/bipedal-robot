# Bipedal robot

Bipedal robot inspired by Cassie from Agility Robotics

## Robot hardware
- Brushless motors 8308 for hip/knee pitch, 6010 for hip roll and yaw and 4008 for toe actuator
- Reduction will be between 10 and 15 for the hip/knee pitch and 30 for hip roll/yaw but not verified mathematically yet
- Reduction might be done with [RV reducer](https://www.youtube.com/watch?v=Ttb4dIUiQWk) to use less bearing/dowels and be easily backdrivable (looks very effective in [Morse Dynamics](https://www.instagram.com/morsedynamics/) robot arm)
- Moteus c1 controller and maybe moteus n1 for hip/knee motors
- Robot control will be done by a Raspberry Pi

## Robot Software:
- Nothing decided for now

## Currently working on
- 3D printing and winding my own motors
- Designing a parametric cycloidal gearbox for each of the different motor size
- Researching robot geometry and joint specs like torque, speed, acceleration
