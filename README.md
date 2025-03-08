# Home Security System Using Arduino

## Team Name: TeeZero7
### Team Members:
- **Avanish Singh** (2114175)
- **Ujjwal Saxena** (2115063)
- **Mukul Tiwari** (2115065)

## Problem Statement
In recent times, burglaries and accidents have been on the rise. To address this issue and ensure a safe environment, we have designed and built a **home security system** using **suitable sensors** in the most efficient way.

## Technologies Used
- **Arduino** (an embedded system combining hardware and software)
- **PIR Sensor** (for motion detection)
- **Ultrasonic Sensor** (for door movement detection)
- **Buzzer** (for alerting unauthorized access)
- **TinkerCAD** (for circuit simulation and design)

## Working Mechanism
Our security system consists of two key sensors:
1. **PIR Sensor**: Detects human motion and triggers the buzzer if any movement is detected.
2. **Ultrasonic Sensor**: Placed near the door, it triggers the buzzer when unauthorized access is attempted.

### Features:
- **Independent Control**: Each sensor has its own switch and can be turned on/off independently.
- **Indoor & Outdoor Security**: The system secures the house whether residents are inside or outside.
- **Bedroom Security**: Since valuables are often stored in bedrooms, the ultrasonic sensor ensures restricted access.

## Efficiency
- **Daytime Usage**: When the user is at home, the PIR sensor can be turned off, but the ultrasonic sensor remains active.
- **Nighttime Usage**: If any unwanted movement occurs, the buzzer is triggered immediately.
- **User Control**: Sensors can be switched off temporarily when required.

## Circuit Design
[TinkerCAD Circuit Design](https://www.tinkercad.com/things/gevhRBtGZqk-daring-kasi/editel?sharecode=qqa8aM9A-K-W_UgHio_OaV7NoNBw69vuX0ci4Cxg1pk)

## Advantages & Disadvantages
### Advantages:
- **Independent operation of sensors**
- **Switchable sensors for user convenience**

### Disadvantages:
- The **PIR sensor** cannot differentiate between humans and animals, which may lead to false alarms if a pet is nearby.

## Future Enhancements
- **GSM Module**: Sends SMS or calls if an intrusion is detected.
- **Fingerprint Door Lock**: Enhances security by restricting access.
- **Camera Integration**: Captures images upon motion detection and sends them via email or smartphone.
- **Laser Tripwire Setup**: Additional security mechanism.
- **AI/ML Implementation**: Improves system efficiency and enables app-based control.
- **Numeric Keypad with LED Display**: Allows secure activation and deactivation of the sensors with a PIN.

## Installation & Usage
1. Connect the sensors and buzzer to the Arduino board as per the **circuit diagram**.
2. Upload the provided **Arduino code** to the board.
3. Use the switches to turn the sensors on/off as required.
4. Test the system by simulating movement and unauthorized access.

---
### Contributors
Feel free to contribute and improve our project. Pull requests and feedback are welcome!

---
### License
This project is open-source and available under the **MIT License**.

