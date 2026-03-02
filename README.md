🔐 ESP32 Smart Security System

📌 Project Overview

This project detects unauthorized entry using a laser–LDR tripwire system and allows secure access through keypad-based password authentication.
All system states and sensor values are monitored in real time using ThingSpeak.

It is designed as a practical embedded systems and IoT learning project.

🚀 Features

🔴 Laser + LDR intrusion detection

🔐 4x4 Keypad password authentication

👆 Touch sensor to initiate authentication

🚨 Buzzer + LED alarm system

📡 Real-time data monitoring on ThingSpeak

🔄 Automatic system reset (no manual reset button)

⚡ Hardware-calibrated for accurate detection

🧠 System Logic

1️⃣ System stays in Armed Mode
2️⃣ If laser beam is broken → 🚨 Alarm triggers
3️⃣ Touch sensor activates password mode
4️⃣ Correct PIN → ✅ Access Granted
5️⃣ Wrong PIN / Timeout → 🚨 Alarm
6️⃣ System auto-resets after defined time

📊 ThingSpeak Fields

Field 1 → LDR Value

Field 2 → Alert Status (0 = Normal, 1 = Intrusion)

Field 3 → System State

0 → Armed

1 → Authentication Mode

2 → Access Granted

# 🔐 ESP32 Smart Security System

[![Project Demo](https://img.youtube.com/vi/MlaIxdVTejI/0.jpg)](https://youtu.be/MlaIxdVTejI)
