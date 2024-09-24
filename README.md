# IOT_Cradle_Project
Smart Baby Cradle with Ultrasonic and Sound Sensors.

Overview:
This project is a Smart Baby Cradle system using an Arduino Uno. The system detects when a human (such as a baby) is near the cradle and rings/beeps a buzzer. Additionally, it monitors the baby's crying using a sound sensor and automatically swings the cradle to comfort the baby. The system continuously monitors the surroundings using the ultrasonic sensor and sound sensor. If a person is detected within 5 cm, the buzzer will ring. If a baby’s cry is detected, the servo motor will swing the cradle.

Features:
Human Detection: Uses an ultrasonic sensor (HC-SR04) to detect if someone is within 5 cm of the cradle and rings a buzzer.
Cry Detection: Detects baby crying (90 decibels) using a sound sensor (KY-037) and swings the cradle using a servo motor (SG90).
Automated Motion: Simulates a rocking motion by rotating the servo motor between 0° and 180° when crying is detected.
Modular Code: Easy to modify and extend for additional features.

Software: ArduionIDE
Components:
Arduino Uno
Ultrasonic Sensor (HC-SR04)
Sound Sensor (KY-037)
Servo Motor (SG90)
Buzzer
Breadboard, USB and Jumper Wires

Libraries Used:
Servo: For controlling the SG90 servo motor.
NewPing: For controlling the ultrasonic sensor and measuring distances.

