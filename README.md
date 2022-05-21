# Parking_Sensor
Repository for the project about simulating the parking sensor via an STM board and peripheries

1. STM32L476 Discovery - microprocessor
2. LSM303C - accelerometer
3. L3gd20 - gyroscope
4. HC-SR04 - ultrasonic sensors
5. Buzzer

Main idea:
When the sensors detect the object close to the construction the buzzer starts to play.
If the acceleration is high and object is close there is a save to external memory of the board.

From the save you can read data: time, date, acceleration in XY, dps in XY and the distance to the obstacle
