# Parking_Sensor
Repository for the project about simulating the parking sensor via an STM board and peripheries

Hardware:
1. STM32L476 Discovery - microcontroler with peryferials,HC-SR04 - ultrasonic sensor,
2. LSM303c - accelerometer,
3. Buzzer,
4. L3GD20 - gyroscope,
5. Module with analog-digital multiplexer 74HC4051.

Software:
1. Stm32CubeIDE - IDE for programming microcontroeler,
2. Qt - a set of libraries and tools for visualization

Main idea:
When the sensors detect the object close to the construction the buzzer starts to play.
If the acceleration is high and object is close there is a save to external memory of the board.

From the save you can read data: time, date, acceleration in XY, dps in XY and the distance to the obstacle
