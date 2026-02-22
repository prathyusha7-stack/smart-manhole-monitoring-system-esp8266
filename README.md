# Smart Manhole Monitoring System (ESP8266)

# Project Overview
This project is an IoT-based Smart Manhole Monitoring System developed using ESP8266 (NodeMCU).
The system detects open manholes and overflow conditions in real time and provides alerts using an LCD display and buzzer.
The main goal is to improve public safety and reduce accidents caused by unattended manholes.

# What I Have Done:-
- Designed and implemented a hardware-based monitoring system.
- Programmed ESP8266 using Arduino IDE.
- Integrated sensors to detect lid opening and water overflow.
- Displayed real-time status on LCD.
- Activated buzzer during abnormal conditions.
- Tested the system with different scenarios.

# Hardware Components Used

- ESP8266 (NodeMCU)
- 16x2 LCD Display
- Float Sensor (Water Level / Overflow Detection)
- IR / Switch Sensor (Manhole Lid Detection)
- Buzzer
- Connecting wires & power supply

# System Logic

The system continuously reads sensor values and checks conditions:

1️. Normal Condition
If Lid closed
No overflow
👉 LCD shows: "Everything Fine"
👉 Buzzer OFF 

2️. Manhole Open
If Lid sensor triggered
👉 LCD shows: "Manhole Opened"
👉 Buzzer ON

3️. Overflow Condition
Water level sensor triggered
👉 LCD shows: "Overflow"
👉 Buzzer ON

4️. Dangerous Condition
Both sensors triggered
👉 LCD shows: "Danger"
👉 Buzzer ON

🎯 Applications
- Smart City Infrastructure
- Municipal Safety Monitoring
- Accident Prevention Systems
- Urban Drainage Monitoring

🚀 Future Improvements
- Add gas sensor for toxic gas detection
- Add cloud-based notification system
- Add mobile application
- Store data in online database



  

