# AI-Based Indian Currency Recognition System using ESP32-CAM and TinyML

## Overview

This project is an embedded AI-based currency recognition system designed for visually impaired individuals. The system uses ESP32-CAM and TinyML to recognize Indian currency denominations in real time.

The camera captures the currency note image, the machine learning model predicts the denomination, and buzzer patterns indicate the detected note.

---

## Features

- Real-time Indian currency recognition
- TinyML inference on ESP32-CAM
- Flash-assisted image capture
- Majority voting for stable prediction
- Buzzer-based denomination output
- Offline operation (No internet required)

---

## Hardware Components

- ESP32-CAM AI Thinker
- OV2640 Camera Module
- Active Buzzer
- LED Flash

---

## Software Used

- Arduino IDE
- Edge Impulse
- C++
- TinyML

---

## Working Principle

1. Camera captures note image
2. Image preprocessing occurs
3. TinyML model performs inference
4. Multiple frame predictions are taken
5. Majority voting selects final output
6. Buzzer indicates denomination

---

## Dataset Classes

- ₹10
- ₹20
- ₹50
- ₹100
- ₹200
- ₹500

---

## Model Performance

Validation Accuracy: ~79%

The model performance was improved using majority voting across multiple frames to reduce unstable predictions.

---

## Hardware Setup

![Hardware Setup](https://github.com/krishnaSutar00/Currency-Recognition-esp32/blob/main/Hardware_Images/WhatsApp%20Image%202026-05-20%20at%202.06.26%20PM.jpeg?raw=true)
---

## Results

### Serial Monitor Output

![Serial Monitor](https://github.com/krishnaSutar00/Currency-Recognition-esp32/blob/main/Results/Serial_Monitor_Output.jpeg?raw=true)

---

## Future Improvements

- Voice output for accessibility
- Mobile application support
- Improved dataset quality
- Higher accuracy model

---

## Author

Nick
