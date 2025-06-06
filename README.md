# 👓 Smart Glasses for the Visually Impaired  
### Third Year Mini Project by Team NEXUS4

This project presents a wearable smart glasses system built around the **ESP32-CAM** platform, designed to aid visually impaired individuals by detecting nearby objects and providing audio notifications in real time.

---

## 🚀 Key Features

- Real-time object recognition powered by **ESP32-CAM**
- Voice announcements of detected objects for user awareness
- Portable design powered by a **rechargeable battery**
- Provides immediate alerts to assist **navigation and safety**

---

## 🔧 Components Used

- ESP32-CAM module  
- 3000mAh Rechargeable Li-ion Battery  
- TP4056 Battery Charging Module  
- MT3608 DC-DC Step-up Booster  
- MAX98357A Mini Audio Amplifier  
- 4Ω 5W Speaker  
- Optional OLED Display for visual feedback  

---

## 💻 Software & Development Tools

- **Arduino IDE** for programming  
- **Edge Impulse** platform for training custom detection models  
- **GitHub** for version control  
- Libraries used:
  - `WiFi.h`  
  - `WebServer.h` or `ESPAsyncWebServer.h`  
  - `esp_camera.h`  
  - `esp_timer.h`  
  - and more...

---

## 🛠️ System Operation

1. The **ESP32-CAM** continuously captures live video data.  
2. A tailored **AI model** identifies objects within the scene on the fly.  
3. Detected object names are transmitted as **audio signals** through the amplifier to the speaker, notifying the wearer.

---

## 📈 Planned Future Upgrades

- Integration with **Raspberry Pi** to enable:
  - Facial recognition  
  - Text reading using OCR  
- Addition of **ultrasonic or LiDAR sensors** for better spatial awareness  
- Use of advanced AI frameworks like **YOLO** and **cloud-based models**  
- Bluetooth support for **smartphone connectivity** and notifications  
- **On-device AI** for interpreting environments and narrating surroundings  
- **OCR-based Braille translation** with multi-language **text-to-speech**  
- **GPS-enabled navigation** with:
  - Voice guidance  
  - Obstacle warnings  
  - Emergency SOS alerts  

---

## 🙏 Gratitude

We extend our heartfelt thanks to our mentor **Prof. Agi George** and technical advisor **Ms. Therese Yamuna Mahesh** for their unwavering support, guidance, and encouragement throughout this project journey.

---

> **Developed with passion by Team NEXUS4 | 2025**
