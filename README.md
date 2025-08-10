# 🛡️ Motion Detection Camera with Face, Eye & Color Tracking

This project is a **real-time motion detection and alert system** using **OpenCV**, **NumPy**, and **Pygame**.  
It detects **faces**, **eyes**, **movement**, and **blue-colored objects** via a webcam feed and triggers an **alarm** when motion or a blue object is detected.

## 📌 Features
- **Face & Eye Detection**: Uses Haar cascades for real-time face and eye tracking.
- **Motion Detection**: Background subtraction to detect moving objects.
- **Color Tracking**: Detects blue objects using HSV color filtering.
- **Alarm System**: Plays an alarm sound when motion or a blue object is detected.
- **Live Video Feed**: Displays bounding boxes for detected items.

## 🛠️ Requirements
Install the required Python libraries before running:
```bash
pip install opencv-python numpy pygame
