# 🛑 Real-Time Object & Collision Detection with Telegram Alerts

A real-time surveillance and safety system that uses computer vision to detect objects and collisions. When a critical event is detected, the system captures an image, fetches the location, and sends an alert to a configured Telegram bot.

---

## 🚀 Key Features

- 🎥 **Webcam-Based Detection**  
  Uses OpenCV to process live video feed and identify potential objects or collisions.

- 📸 **Image Capture on Detection**  
  Automatically captures the frame when a collision or object is detected.

- 📍 **Location Tracking**  
  Fetches the current geolocation of the system/device (if available).

- 📲 **Instant Telegram Alerts**  
  Sends real-time alerts with images and location data to a pre-configured Telegram bot.

- 🧠 **Customizable Detection Logic**  
  Flexible architecture to fine-tune sensitivity or detection criteria.

---

## ⚙️ Tech Stack

| Component       | Technology Used                    |
|----------------|-------------------------------------|
| Language        | Python                              |
| Backend         | Flask                                |
| Computer Vision | OpenCV                               |
| Notifications   | Telegram Bot API                     |
| Frontend        | HTML, CSS (Optional Dashboard)       |
| Location API    | geopy, geocoder, or IP-based lookup  |



