# Line-following-buggy-gantry-detection
Autonomous line-following buggy with IR sensing, obstacle avoidance, and gantry detection using Arduino + Eagle CAD
# What it does
- Follows a black line track using dual IR sensors
- Detects obstacles via ultrasonic sensor (HC-SR04) and halts safely
- Detects gantries placed along the track by decoding transmitted pulse widths
- Receives start/stop commands wirelessly via XBee/Zigbee
# Circuit Design
Schematics and PCB layouts designed in Eagle CAD for three circuits:
- IR Receiver (LM311N comparator)
- IR Sensor Module(LM358P)
- PWM Transmitter (ATtiny85)
# Tools Used
Arduino IDE, Eagle CAD, C++, XBee/XCTU

<img width="3060" height="4080" alt="WhatsApp Image 2026-08-24 at 07 03 26 (2)" src="https://github.com/user-attachments/assets/7643315b-7e8a-4d76-a887-809b172b32cc" />
