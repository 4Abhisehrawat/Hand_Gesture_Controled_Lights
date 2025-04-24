# 🤚💡 Hand Gesture Controlled Light using OpenCV & ESP32

This project demonstrates a contactless smart light control system using hand gesture recognition and an ESP32 microcontroller. The system detects specific hand gestures through a webcam feed using OpenCV and `cvzone`, and sends serial commands to the ESP32 to switch the light ON or OFF.

---

## 🔧 Tech Stack

- **Python 3.11**
- **OpenCV**
- **cvzone**
- **ESP32**
- **Arduino IDE (C++)**
- **Serial Communication (UART)**

---

## 📌 Features

- Detects hand gestures using a webcam
- Controls light using ESP32 via serial port
- Real-time response with FPS monitoring
- Works fully offline (no Wi-Fi required)
- Reliable, low-latency control

---

## 📷 Gesture Control Logic

| Gesture | Fingers Detected     | Action         |
|---------|----------------------|----------------|
| ☝       | Index only           | Turn Light ON  |
| ✌       | Index + Middle       | Turn Light OFF |

---

## 🖥️ Python Side (Gesture Detection)

### 🔗 Required Libraries

Install these libraries using pip:

```bash
pip install opencv-python mediapipe cvzone
