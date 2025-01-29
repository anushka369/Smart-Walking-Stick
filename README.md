# Smart Walking Stick 👨‍🦯

This project aims to create a smart walking stick designed for visually impaired individuals. The walking stick uses an ultrasonic sensor to detect obstacles and provides real-time feedback through a buzzer and LED. The feedback varies based on the proximity of objects, helping users navigate their surroundings safely.

---

## Overview 🪫

The Smart Walking Stick utilizes an ultrasonic sensor (HC-SR04) to measure the distance between the user and nearby obstacles. Based on the detected distance, the system activates a buzzer and LED for auditory and visual feedback:

- **Close proximity (< 20 cm)**: Continuous beep with LED on.
- **Medium proximity (20-40 cm)**: Faster beeps with LED on.
- **Far proximity (40-60 cm)**: Slower beeps with LED on.
- **Safe distance (> 60 cm)**: No beep, and LED off.

The system is powered by an Arduino and includes the following components:

- **HC-SR04 Ultrasonic Sensor**: For distance measurement.
- **Buzzer**: For auditory feedback.
- **LED**: For visual feedback.

---

## Components Required ⚡

- Microcontroller (Arduino Uno)
- HC-SR04 Ultrasonic Sensor
- Audio Buzzer
- Light Emiting Diode
- Jumper Wires
- Cable / zip tie
- Power Supply
- Cane frame

---

## Wiring 🔌

1. **HC-SR04 Ultrasonic Sensor**:
   - VCC -> 5V
   - GND -> GND
   - TRIG -> Pin 9 (Digital)
   - ECHO -> Pin 10 (Digital)

2. **Buzzer**:
   - Positive leg -> Pin 11 (Digital)
   - Negative leg -> GND

3. **LED**:
   - Anode (long leg) -> Pin 13 (Digital)
   - Cathode (short leg) -> GND

---

## Setup Instructions 🪜

1. Connect the components as mentioned above.
   
2. Open the Arduino IDE and paste the provided code.
   
3. Upload the code to your Arduino board.
   
4. Open the Serial Monitor to view the distance measurements.

---
   
## Features 🔎

- **Obstacle Detection:** Alerts the user of nearby obstacles.
- **Real-time Feedback:** Audible and visual feedback for better navigation.
- **Adjustable Sensitivity:** Can be modified for different distance thresholds.

---

## Future Enhancements 💰

- **Vibration Feedback:** Add a vibration motor for tactile feedback.
- **Advanced Detection:** Incorporate additional sensors (e.g., infrared) for better accuracy.
- **GPS Integration:** Integrate GPS for outdoor navigation.

---

## Contributing 🤝

This is a personal learning project, but contributions and suggestions are welcome! 
<br> If you find any improvements, feel free to create a pull request. To contribute:

1. Fork the repository.

2. Create a new branch for your feature/bug fix.

3. Commit your changes and submit a pull request.

---

## Authors 📎

- Anushka Banerjee [@anushka369](https://github.com/anushka369)
- Shashank Singh [@shashankexore](https://github.com/shashankexore)

---
