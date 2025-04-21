🤖 Biped Robot (OTTO-Inspired) Using Arduino Nano
This is an interactive, Arduino Nano-based bipedal robot inspired by the OTTO design. It can walk, jump, and avoid obstacles using 4 servo motors and an ultrasonic sensor. It also reacts with sound using a buzzer and includes an assembly mode for easy setup.

🧩 Components
Arduino Nano + Nano Shield
4x 360° Servos
HC-SR04 Ultrasonic Sensor
Active Buzzer
DPDT Push Switch
Battery Holder & Connectors
Jumper Wires

🔧 Features
Walking, Jumping, Turning
Obstacle detection (less than 15 cm)
Audio feedback using buzzer
Assembly mode via push switch
Fully programmable with Otto9 library

⚙️ How It Works
Upload the code using Arduino IDE.
The robot enters assembly mode if Pin 7 is LOW.
In operation mode, it walks forward and reacts to obstacles:
Jumps back
Moves backward
Turns left to find a path

📚 Libraries Required
Otto9 library (for movement and sounds)
