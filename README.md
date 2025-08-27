# Triple-Ultrasonic-and-IR-Sensor-Based-Reverse-Car-Parking-System
# Smart Car Parking System using Triple Ultrasonic Sensors

This repository contains my project on designing a **smart car parking assistance system** using **three ultrasonic sensors** and an **Arduino microcontroller**.  
The project aims to assist drivers in parking by detecting the distance between the car and nearby obstacles, ensuring safer and more efficient parking in tight spaces.

---

##  Motivation
Parking in congested spaces is often difficult and can lead to **minor accidents, scratches, or collisions**.  
A reliable and low-cost parking assistance system can greatly improve safety and convenience for drivers.  

This project demonstrates how **ultrasonic sensors**, combined with a simple microcontroller, can provide **real-time obstacle detection** and **distance estimation**, forming the basis for modern parking assistance technologies.

---

##  System Overview
### Hardware
- **Arduino Uno** → Main controller for sensor integration and decision-making.  
- **Three HC-SR04 Ultrasonic Sensors** → Placed at front, left, and right to measure distance from obstacles.  
- **Buzzer/LED Indicators** → Provide warning signals when obstacles are too close.  
- **Power Supply** → Standard 5V for Arduino and sensors.  

### Software & Tools
- **Arduino IDE** → For programming the microcontroller.  
- **C/C++** → To implement sensor integration and distance calculation.  

---

##  Methodology
1. **Sensor Placement**
   - Three ultrasonic sensors positioned to cover **front, left, and right** blind spots of the vehicle.  

2. **Distance Measurement**
   - Each sensor measures distance using the principle of **time-of-flight** of ultrasonic waves.  
   - Distance calculated using the formula:  
     \[
     \text{Distance} = \frac{\text{Speed of Sound} \times \text{Time}}{2}
     \]

3. **Decision Algorithm**
   - Threshold distances defined (e.g., <20 cm = Danger Zone).  
   - Based on readings, buzzer/LED provides **stepwise warnings** (safe → caution → danger).  

4. **Output Feedback**
   - **LEDs** change color or **buzzer frequency** increases as objects come closer.  

---

##  Results
- Reliable detection of obstacles up to **2–3 meters** away.  
- Real-time feedback helped simulate safe parking in constrained environments.  
- Demonstrated feasibility of **low-cost DIY parking assistance system**.  

---


