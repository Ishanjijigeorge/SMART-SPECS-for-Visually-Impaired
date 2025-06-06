Third Year Mini Project by Team NEXUS4

Smart Glasses for the Visually Impaired

This project presents a wearable smart glasses system built around the ESP32-CAM platform, designed to aid visually impaired individuals by detecting nearby objects and providing audio notifications in real time.

👓 Key Features

Real-time object recognition powered by ESP32-CAM

Voice announcements of detected objects for user awareness

Portable design powered by a rechargeable battery

Provides immediate alerts to assist navigation and safety

🔧 Components Used

ESP32-CAM module

3000mAh Rechargeable Li-ion Battery

TP4056 Battery Charging Module

MT3608 DC-DC Step-up Booster

MAX98357A Mini Audio Amplifier

4Ω 5W Speaker

Optional OLED Display for visual feedback

💻 Software & Development Tools

Arduino IDE for programming

Edge Impulse platform for training custom detection models

Version control using GitHub

Libraries including WiFi.h, WebServer.h (or ESPAsyncWebServer.h), esp_camera.h, esp_timer.h, and more

🛠️ System Operation

The ESP32-CAM continuously captures live video data.

A tailored AI model identifies objects within the scene on the fly.

The detected object names are transmitted as audio signals through the amplifier to the speaker, notifying the wearer.

📈 Planned Future Upgrades

Integration with Raspberry Pi to boost computational capability for advanced tasks such as facial recognition and text reading using OCR.

Adding ultrasonic or LiDAR sensors to measure distances for better spatial awareness.

Employing advanced AI frameworks like YOLO and cloud-based models for improved detection accuracy and scene comprehension.

Bluetooth support to enable seamless smartphone connectivity and real-time notifications.

On-device AI to interpret complex environments and narrate surroundings.

OCR-based Braille translation coupled with multi-language text-to-speech functionality.

GPS-enabled navigation providing voice guidance, obstacle warnings, and emergency SOS alerts for enhanced outdoor mobility.

🙏 Gratitude

We extend our heartfelt thanks to our mentor Prof. Agi George and technical advisor Ms. Therese Yamuna Mahesh for their unwavering support, guidance, and encouragement throughout this project journey.

