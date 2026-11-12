
# AUTO RECOVERY FUSE CARRIER FOR RURAL DISTRIBUTION NETWORK

## 1. Project Overview
The Auto Recovery Fuse Carrier is designed to automatically detect and replace faulty fuses in rural electrical distribution networks. The system reduces manual intervention, improves safety and minimizes power interruptions.

## 2. Objectives
- Automatically detect fuse failure.
- Replace faulty fuses using a motor mechanism.
- Reduce electrical hazards to maintenance workers.
- Restore power supply quickly.
- Display fuse status using an LCD.
- Provide fault alerts using a buzzer.

## 3. Hardware Components
- Arduino UNO
- Voltage Sensor
- DC Motor
- Motor Driver (L293D)
- LCD Display (16x2)
- Buzzer
- Power Supply
- Fuse Carrier Mechanism

## 4. Software Requirements
- Arduino IDE
- Embedded C/C++
- Arduino Programming

## 5. Working Principle
The voltage sensor continuously monitors the voltage across the fuse. When a fuse failure occurs, the sensor sends a signal to the Arduino UNO.

The Arduino processes the signal and activates the buzzer and motor mechanism. The motor rotates the fuse carrier to position a new fuse. The system then checks whether voltage has been restored and updates the LCD status.

## 6. Applications
- Rural power distribution networks
- Distribution transformer protection
- Agricultural power supply
- Remote electrical installations
- Smart grid systems

## 7. Advantages
- Automatic fuse replacement
- Reduced manual intervention
- Improved maintenance safety
- Faster power restoration
- Reduced downtime
- Real-time fault indication

## 8. Future Enhancements
- IoT-based remote monitoring
- Mobile application notifications
- Solar-powered operation
- AI-based fault prediction
- Cloud-based fault history

## 9. Project Conclusion
The Auto Recovery Fuse Carrier for Rural Distribution Network provides an automated approach to fuse fault detection and replacement. It improves power distribution reliability, reduces downtime and minimizes the risks associated with manual fuse replacement.

## Project Team
- Project: Auto Recovery Fuse Carrier
- Institution: M. Kumarasamy College of Engineering
- Department: Electrical and Electronics Engineering

---
**Note:** This is an academic prototype and is not certified for live distribution-network operation.
