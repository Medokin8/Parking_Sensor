# Parking_Sensor
Repository for the project about simulating the parking sensor via an STM board and peripheries

Hardware:
• STM32L476 Discovery - microcontroler with peryferials,HC-SR04 - ultrasonic sensor,
• LSM303c - accelerometer,
• Buzzer,
• L3GD20 - gyroscope,
• Module with analog-digital multiplexer 74HC4051.

Software:
• Stm32CubeIDE - IDE for programming microcontroeler,
• Qt - a set of libraries and tools for visualization

Main idea:
When the sensors detect the object close to the construction the buzzer starts to play.
If the acceleration is high and object is close there is a save to external memory of the board.

From the save you can read data: time, date, acceleration in XY, dps in XY and the distance to the obstacle
