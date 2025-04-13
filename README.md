
---

# 🏠 Home Automation Project Using ESP8266 and 4channel Relay

This home automation project demonstrates how to control household appliances using an ESP8266 NodeMCU and a 4-channel relay module. The system connects to Wi-Fi and enables remote control of devices (like a light bulb) via a smartphone or voice commands using Google Assistant. Manual switches are also integrated for local control.

---

## 🔧 Tools & Components

- ESP8266 NodeMCU
- 4-Channel Relay Module
- Manual Switches
- 5V Power Adapter
- Breadboard
- Jumper Wires
- AC Bulb with Holder
- Firmware Flash Tool 
- - [Espressif Flash Tools](https://www.espressif.com/en/support/download/other-tools?keys=)

---

## ⚡ Project Overview

This project controls a 230V AC light bulb using a relay, triggered by the ESP8266. I initially attempted the setup using the Arduino IDE, Blynk, and KME tools, but encountered multiple issues. After several trials and errors, I found a working solution using a prebuilt firmware and the **Cadio flash tool** (version 3.9.8), which I discovered through a YouTube tutorial.

---

## 📷 Project Images

![Image 1](https://github.com/user-attachments/assets/47a4c3e4-b515-414c-8c5e-9b9b27d531c1)  
![Image 2](https://github.com/user-attachments/assets/83ddfa18-c088-4b57-9322-73c8c845b72f)  
![t (3)](https://github.com/user-attachments/assets/021f5f3a-824f-43de-9f47-6e2aea5a0567)
![t (2)](https://github.com/user-attachments/assets/536047c7-3eab-405b-9859-0da7eafbdefa)
![t (1)](https://github.com/user-attachments/assets/f0bfe1e2-1174-4200-9be8-c7138c78a5f4)
![Image 4](https://github.com/user-attachments/assets/a1a8c04e-9f48-44d6-a498-0eeb7df846b8)  
![Image 5](https://github.com/user-attachments/assets/453fce2d-2d4e-4b44-8753-8fd0e69ae4fc) 
![t (4)](https://github.com/user-attachments/assets/f4f172e5-b590-4295-8a10-ad7bd709f5b0)
![Image 6](https://github.com/user-attachments/assets/fb3cfd9e-b944-42ef-9b6e-3bc1fbb17ef0)  
![t (5)](https://github.com/user-attachments/assets/60370f25-b769-426d-8df3-fc11b344ae03)


---

## 📖 My Learning Journey

- Attempted to build the system using Arduino IDE with custom code – unsuccessful.
- Explored other platforms like Blynk and KME tool – not compatible with my setup.
- Faced and resolved challenges related to Wi-Fi connectivity and power supply.
- Discovered a no-code solution using the Cadio flash tool.
- Successfully controlled a real AC bulb through the ESP8266 and relay module.

---

## ✅ Key Features

- Wi-Fi-based remote control
- Voice control via Google Assistant
- Manual switch support
- Works with 230V AC appliances
- No coding required
- Easily expandable for more devices

---

## 🙌 Credits

- YouTube tutorials and community support
- [Cadio Flash Tool Tutorial](https://youtu.be/jKBywXI3hmE?si=8y7WG2uToGUX_ggL)  
- [Espressif Flash Utilities](https://www.espressif.com/en/support/download/other-tools?keys=)

---

## 🧠 What I Learned

- Fundamentals of microcontrollers (ESP8266) and how they interface with relay modules.
- Flashing firmware and solving real-world issues such as:
  - Network connectivity problems
  - Relay not responding
  - Power mismatches
- Gained hands-on experience with tools like Arduino IDE, Blynk, and firmware flashers.
- Built confidence in creating functional hardware prototypes from home.

---
