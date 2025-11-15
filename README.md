# Room Automation System Using Cisco Packet Tracer project using cisco pkt

📄 Submission Statement

This project titled “Room Automation System Using Cisco Packet Tracer” is submitted by Group 3 as part of the Applied Industrial Internet of Things (IIoT) coursework.

👥 Group 3 Members

Kartik – Roll No. 2410996768
Jatin – Roll No. 2410996767
Khushi – Roll No. 2410996769
Kirti – Roll No. 2410996770

We hereby declare that the work presented in this submission is original, completed collaboratively by Group 3, and prepared in accordance with the guidelines provided.

🎯 Aim

To design and simulate a smart IoT-based room automation system using Cisco Packet Tracer, enabling remote monitoring and automated control of appliances.

📝 Problem Statement

Manual control of household appliances leads to inefficiency and higher energy usage.
The goal is to build an IoT-enabled network where devices operate automatically based on sensor input and user configuration.

📡 Network Architecture

Your topology includes:
WRT300N Wireless Router
2950-24 MSW Switch
IoT & Radius Server (Server-PT)
Laptop-PT Client
IoT Devices Connected Over Wi-Fi
Fan (IoT0)
Garage Door (IoT1)
Light (IoT2)
Window (IoT3)
Door (IoT4)
Motion Detector (IoT5)
Thermostat (IoT7)
The central wireless router provides connectivity to all IoT devices, and the IoT server manages automation rules and device authentication.

🔧 Required Components
Software

Cisco Packet Tracer (IoT supported version)
Any text editor (Notepad/VS Code)
GitHub for uploading project
Virtual Hardware (inside Packet Tracer)
Wireless Router (WRT300N)
Switch (2950-24 MSW)
IoT & Radius Server
IoT Devices (Fan, Light, Thermostat, Motion Detector, Garage Door, Door, Window)

⚙️  Automation Rules

1️⃣ Motion Detector → Light Automation

If motion detected → Light ON

If motion NOT detected → Light OFF

2️⃣ Thermostat → Fan Automation 

Controls the fan based on thermostat mode:

✔ If Thermostat Mode = COOL

Fan OFF

✔ If Thermostat Mode = HEAT / HOT

Fan ON

Programming Steps in Cisco Packet Tracer:

Open IoT Server → Programming tab

Rule

Condition: Thermostat.mode == Cool → Action: Fan.turnOff

Condition: Thermostat.mode == Heat → Action: Fan.turnOn

<img width="1513" height="696" alt="Screenshot 2025-11-15 223906" src="https://github.com/user-attachments/assets/757196ed-16d1-40ca-a0a6-03c3e6057097" />


