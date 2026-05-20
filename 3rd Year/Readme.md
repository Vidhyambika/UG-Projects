# Projects

1. [Gender and Age Detection](https://github.com/Vidhyambika/UG-Projects/blob/main/3rd%20Year/Gender%20and%20Age%20Detection.zip")
2. [Compose and Program Music in Python using Earsketch](https://github.com/Vidhyambika/UG-Projects/tree/main/3rd%20Year/Compose%20and%20Program%20Music%20in%20Python%20using%20Earsketch)

# Gender and Age Detection

## Overview
Gender and Age Detection is a Computer Vision and Deep Learning project that predicts the gender and approximate age group of people from uploaded images or live webcam feeds. The project uses OpenCV DNN models with pre-trained Caffe models for real-time face, gender, and age detection.

## Features
- Detect faces from images and webcam
- Predict gender (Male/Female)
- Estimate age groups
- Real-time live camera detection
- Supports single and multiple face detection
- Displays predictions directly on the video frame

## Technologies Used
- Python
- OpenCV
- Deep Learning
- CNN
- Caffe Models

## Project Files
- `gad.py` → Main Python script
- `opencv_face_detector.pbtxt` → Face detection configuration
- `opencv_face_detector_uint8.pb` → Face detection model
- `gender_deploy.prototxt` → Gender model configuration
- `gender_net.caffemodel` → Gender prediction model
- `age_deploy.prototxt` → Age model configuration
- `age_net.caffemodel` → Age prediction model

## How It Works
1. Captures image or webcam stream
2. Detects faces using OpenCV DNN
3. Extracts facial regions
4. Predicts:
   - Gender
   - Age group
5. Displays results in real time

## Age Groups
The model predicts the following age ranges:
- 0–2
- 4–6
- 8–12
- 15–20
- 25–32
- 38–43
- 48–53
- 60–100

## Installation
```bash
pip install opencv-python
```

## Run the Project

### Webcam Detection
```bash
python gad.py
```

### Image Detection
```bash
python gad.py --image image.jpg
```

## Applications
- Smart surveillance systems
- Retail analytics
- Demographic analysis
- Human-computer interaction
- AI-powered camera systems

## Future Enhancements
- Improve prediction accuracy
- Add emotion detection
- Deploy as a web application
- Mobile app integration

## Author
Vidhyambika
