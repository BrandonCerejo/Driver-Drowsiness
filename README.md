# Driver Drowsiness Detection and Alert System 🚘

A real-time driver monitoring system built with Python, optimized for Raspberry Pi, to enhance road safety by detecting signs of drowsiness through facial landmark analysis. The system identifies prolonged eye closure and yawning and triggers alerts to keep the driver awake.

## 🌟 Features

- Real-time Monitoring
  - Eye aspect ratio (EAR) for detecting drowsiness
  - Lip distance measurement for yawning detection
  - Alert System

- Audio alerts for prolonged drowsiness
  - Notifications to prompt driver action
  - Facial Landmark Detection

- Haar cascades for face detection
  - Dlib’s pre-trained model (shape_predictor_68_face_landmarks.dat) for precise landmark identification

## 🔧 Technologies Used

- **Raspberry Pi and Camera Module or compatible USB camera**
- **Dlib** - Facial Landmark Detection
- **OpenCV** - Real-time Video Processing
- **Threading** - Concurrent Alert System

## 📋 Prerequisites

- Python 3.x (Compatible with Raspberry Pi)
- OpenCV and Dlib installed on Raspberry Pi

## 🚀 Installation

1. Clone the repository onto the Raspberry Pi:

```bash
git clone <repository_url>  
cd <repository_directory>
```

2. Install required dependencies as listed above.
   
3. Set up the Raspberry Pi Camera or attach a compatible USB camera.

## 🔄 Workflow

1. Face Detection: Detects the driver's face using Haar cascades.

2. Facial Landmark Analysis: Monitors eye closure through EAR. Tracks yawning through lip distance measurement.

3. Alert Trigger: Initiates audio alerts for detected drowsiness or yawning.

## 🎯 Outcome

A practical and efficient system to minimize accidents by detecting driver fatigue in real-time, tailored for Raspberry Pi deployment.

## Output Images

![output6](https://github.com/user-attachments/assets/76c6207b-4132-4dbc-8268-b5dc2b0e67e1)

![output5](https://github.com/user-attachments/assets/70fc930d-f507-4100-b22c-4b26e602360f)
