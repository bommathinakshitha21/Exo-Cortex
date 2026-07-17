# Exo-Cortex
An AI powered add-on to helmets that can help save lives
## Over view
Every year, thousands of motorcyclists lose their lives because emergency services arrive too late. Standard helmets only offer passive, physical protection. 
The project “Exo-Cortex” is a helmet add-on that lives during road accidents. Most smart helmets or their add ons, are expensive and are inaccessible to an average middle class driver. Our project is a budget-friendly, hardware-and-software add-on that transforms any standard helmet into a life-saving device.  

By pairing the helmet with a smartphone app, the system monitors rider speed and detects accidents in real-time. In the event of a crash, the app automatically triggers phone calls and SMS alerts containing the rider's precise GPS location to their emergency contact.

## Key features

## 1.Crash detection through mobile app:
The hardware add-on is connected to a mobile app, through GPS, and speed detection, the app will be able to detect a crash, accident and over speeding.

## 2.Automatic emergency SOS: 
The user will give an emergency contact while setting up the mobile app, where the hardware or the app detects a crash, a call and a message will be sent to the contact given by the user. 

## 3.Hands free assistance integration:
A switch/button on the helmet which is attached to the hardware or add on will activate an assistant the user can speak and give command to, during emergency.

## 4.Infrastructure audio alert: 
The user will get alerted before any traffic jam, potholes, or bad roads.

## 5.Good battery life:
The hardware/add on part gives four to five hours of battery life.

## 6.Quick snap magnetic dock:
The hardware is attached to the helmet using magnetic force, which is easy to attach and remove.

## Tech Stack 

### Hardware Stack
* **Microcontroller:** ESP32 Development Board (WROOM)
* **DAC / Amplifier:** MAX98357A I2S Module
* **Power Source:** 3.7V Li-Po Battery (800-1000mAh)
* **Battery Management:** TP4056 Type-C Charger
* **Audio Output:** Flat Helmet Speakers (30mm)
* **Physical Interface:** Handlebar Tactile Switch (Push Button)

### Software Stack
* **Language:** C++ (Object-Oriented Firmware)
* **IDE & Toolchain:** PlatformIO inside Visual Studio Code (VS Code)
