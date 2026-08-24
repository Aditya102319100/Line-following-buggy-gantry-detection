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

<img width="3060" height="4080" alt="WhatsApp Image 2026-08-24 at 07 03 26 (2)" src="https://github.com/user-attachments/assets/a9bdf748-b196-4ee4-94c9-95c78016d898" />
<img width="1600" height="1200" alt="WhatsApp Image 2026-08-24 at 07 03 26 (1)" src="https://github.com/user-attachments/assets/472eafb0-0ef4-45c0-bace-c8fd76b9ba75" />
<img width="1200" height="1600" alt="WhatsApp Image 2026-08-24 at 07 03 26" src="https://github.com/user-attachments/assets/55b69b24-f07a-4df8-a45e-648b96330345" />
<img width="3072" height="4096" alt="WhatsApp Image 2026-08-24 at 07 03 27" src="https://github.com/user-attachments/assets/48a6fad3-03a8-49a8-af3b-145b8ada58d7" />
