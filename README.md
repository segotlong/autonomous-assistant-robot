 autonomous-assistant-robot

  Assistive Following Robot

This project focuses on building an **assistive following robot** designed to help users carry light items and follow them autonomously.  
It was built using an **Arduino Nano BLE 33 Sense** and **ESP32**, combined with DC motors, ultrasonic sensors, and a motor driver.

 Project Overview

The aim was to design and program a robot that could detect and follow a person or object while maintaining a safe distance.  
It integrates motion sensing, distance tracking, and motor control — combining software logic with physical design to produce an assistive solution.


 Components Used

| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino Nano BLE 33 Sense | 1 | Main microcontroller for robot logic |
| ESP32 Development Board | 1 | Handles sensor input and Bluetooth communication |
| L298N Motor Driver | 1 | Controls the two DC geared motors |
| DC Geared Motors (12V with encoders) | 2 | Drive movement |
| Ultrasonic Sensors | 2 | Detect distance and obstacles |
| Servo Motor | 1 | Moves the bins or attachments |
| Li-ion Battery Holder | 1 | Power supply |
| Step-down Regulator | 1 | Maintains stable 5V for electronics |
![1000055664](https://github.com/user-attachments/assets/4f3b2ce9-9d96-4e90-b18c-c0ef09323ddd)


  System Design

- **Movement:** Controlled by two DC motors via L298N driver  
- **Distance Tracking:** Ultrasonic sensors measure range and ensure safe following distance  
- **Control Logic:** Arduino Nano BLE 33 Sense manages motor signals based on sensor feedback  
- **Communication:** ESP32 used for external control and wireless monitoring  
<img width="395" height="753" alt="pic 44" src="https://github.com/user-attachments/assets/f41b3bf3-ea86-440d-b826-abe7c5050cfc" />
![1000068388](https://github.com/user-attachments/assets/904018bf-60b7-45ed-9888-e975834228d8)

---

##  Software Development

The robot was coded in **Arduino IDE**.  
Main features included:
- Motor control using PWM signals  
- Ultrasonic distance measurement  
- Conditional following behavior (move forward, stop, or turn)  
- Communication setup between ESP32 and Nano BLE 33 Sense  
<img width="1346" height="667" alt="pic 75" src="https://github.com/user-attachments/assets/14a4faa6-515e-491c-afc1-217f97d058a1" />
<img width="1333" height="721" alt="pic 76" src="https://github.com/user-attachments/assets/0704ace6-9397-4ea1-9eed-25a4f99d31a9" />


---

##  Testing and Improvements

Challenges faced:
- Calibrating ultrasonic sensors for accurate detection  
- Adjusting motor speed for smooth following  
- Ensuring proper power regulation from the Li-ion batteries  

Future improvements:
- Integrate object recognition using a camera module  
- Add Bluetooth remote control via MIT App Inventor  

---

##  Demonstration


---

##  Tools & Resources

| Resource | Purpose | Link |
|-----------|----------|------|
| Arduino IDE | Programming & testing | [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software) |
| Tinkercad | Circuit simulation | [https://www.tinkercad.com](https://www.tinkercad.com) |
| Random Nerd Tutorials | Reference for motor & ESP32 guides | [https://randomnerdtutorials.com](https://randomnerdtutorials.com) |
| MIT App Inventor | Bluetooth control testing | [https://appinventor.mit.edu](https://appinventor.mit.edu) |

---

 **Created by:** *Mosa Segotlong
 *2025*  
 *An assistive robot designed to support daily tasks through automation and smart design.*

---
