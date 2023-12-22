# Alcohol-detection-and-engine-lock-system
This project presents the design and implementation of an Alcohol Detection and Engine 
Locking System for cars and other vehicles using an Arduino Nano as the MCU (Master 
Control Unit) and a MQ3 Sensor as the detection device for alcohol. The system 
continuously monitors the alcohol level in its affinity using the MQ3 sensor, and as soon 
as the concentration of alcohol goes beyond the threshold level, the engine gets locked 
and a buzzer starts to beep/buzz to give indication to the nearby vehicles that the 
particular vehicle’s driver is drunk and it is not safe to drive nearby the vehicle, and is a 
threat to other people on the road. The MQ3 Sensor senses alcohol and sends a signal to 
the Arduino. On receiving the signal from the sensor, the Arduino send a signal to the 
Buzzer and the Relay, which cuts the power supply to the motor, making the car STOP 
and preventing any mishap.

# Objective of the Project
Every system is automated in order to face new challenges. In the present days Automated systems have fewer manual operations,flexibility,
reliability and accurate. Due to this demand every field prefers automated control systems. We usually come across drink and driving cases where
drunk drivers crash their cars under the influence of alcohol
causing damage to property and life. So here we propose an innovative system to eliminate such cases. 

Our proposed system would be constantly monitoring the driver breath by placing it on the driver wheel or somewhere the driver’s breath can be constantly 
monitored by it. So, if a driver is drunk and tries to drive the system detects alcohol presence in his/her breathe and locks the engine so that the 
vehicle fails to start. In another case if the driver is not drunk while he starts the vehicle and engine is started but he/she drinks while driving 
the sensor still detects alcohol in his breath and stops the engine so that the car would not accelerate any further and driver can steer it to roadside. 
So, the alcohol sensor is used to monitor uses breath and constantly sends signals to the microcontroller.

# Circuit Diagram
![normal diagram](https://github.com/dignagpakhare/Alcohol-detection-and-engine-lock-system/assets/150357421/440b5777-0771-44c3-b3b7-72cb7fe4ab6c)

# Parts Used
```
 Parts Used in this Project
├── Arduino UNO
├── MQ-3 SENSOR
├── 16x2 LCD Display
├── Relay
├── Switch
├── Buzzer
