# 4WD-Tank-robot-car
Adaptation of STEVAL-FCU001V1 drone STM32F401 FW project for 4WD DC motor tank robot car project.

It's possible to control the tank robot car both with STDrone BLE app (for Android) or with a PWM remocon receiver.
Few adaptations done to the original project to can control the 4 DC motors removing the stabilization control algo needed
for a drone.

Car is very fast and responsive and ok to be used in indoor condition. For outdoor condition need to integrate a PID control
to can keep straight direction also on tough terrain, NOT YET IMPLEMENTED.

Further possible implementations:
- PID control for outdoor condition
- Ultrasound distance sensor HC-SR04
- Communication with Raspberry Pi ZeroW for advanced functions
- Servo motor for camera
