# Third Year Mini Project by our team - NEXUS4

## Smart Specs for the Visually Impaired

This is a wearable device built using the **ESP32-CAM** to assist visually impaired people by detecting nearby objects and announcing them through audio feedback.

---

### 👓 Features

- Real-time object detection using ESP32-CAM  
- Audio output for detected objects  
- Battery-powered wearable design  
- Alerts the user immediately  

---

### 🔧 Hardware Used

- ESP32-CAM  
- Rechargeable Li-ion Battery (3000mAh)  
- Charging module (TP4056)  
- Booster module (MT3608)  
- Mini Audio Amplifier (MAX98357A)  
- Speaker (4Ω 5W)  
- OLED Display (optional)  

---

### 💻 Software & Tools

- Arduino IDE  
- Edge Impulse (for object detection model)  
- GitHub (version control)  
- Libraries used: `WiFi.h`, `WebServer.h` (or `ESPAsyncWebServer.h`), `esp_camera.h`, `esp_timer.h`, etc.  

---

### 🛠️ How It Works

- The ESP32-CAM captures video input continuously.  
- A custom-trained model detects objects in real-time.  
- The detected object's name is sent as audio to an amplifier and played through a speaker.  

---

### 📈 Future Enhancements

- Raspberry Pi integration for enhanced processing power, enabling:  
  - Real-time object detection  
  - Facial recognition  
  - OCR-based text reading  
- Integration with ultrasonic or LiDAR sensors for depth perception  
- Use of YOLO, Edge Impulse, and cloud-based AI for better accuracy and scene understanding  
- Bluetooth connectivity for real-time updates via smartphone  
- Onboard AI for enhanced environment description  
- Braille text-to-speech conversion using OCR and multilanguage TTS  
- GPS navigation providing voice-guided directions, obstacle alerts, and emergency SOS  

---

### 🙏 Acknowledgements

Special thanks to our guide **Prof. Agi George** and **Ms. Therese Yamuna Mahesh** for their constant support and technical mentorship throughout this project.
