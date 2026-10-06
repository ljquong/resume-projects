## Autonomous Delivery Robot
A class project involving the development of embedded software for a line-following delivery robot. The robot was programmed to navigate a course, detect and collect a payload, and deliver it to a designated drop-off area.

### Overview
The robot uses a Raspberry Pi Pico running MicroPython to control its motors and servos while responding to input from multiple sensors. 

### Implementation
- Controlled two DC motors using GPIO
- Used a black line sensor for navigation
- Used a reed switch to detect the payload
- Used an IR sensor to detect the drop-off area
- Controlled three servos for payload handling
- Implemented motor speed corrections to compensate for differences between motors
- Wrote test scripts to evaluate component behaviour during development

### What I Learned
This project gave me experience working directly with embedded hardware and integrating software with physical components. I learned how differences in hardware behaviour can affect software, such as when the two motors required different speed corrections to keep the robot moving as intended. Testing individual components and tuning their behaviour was an important part of getting the system to work reliably. 
