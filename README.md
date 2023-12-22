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

![normal diagram](https://github.com/dignagpakhare/Alcohol-detection-and-engine-lock-system/assets/150357421/440b5777-0771-44c3-b3b7-72cb7fe4ab6c)

# Components
1. Arduino UNO
2. MQ-3 SENSOR
3. 16x2 LCD Display
4. Relay
5. Switch
6. Buzzer
