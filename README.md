# AI-Based Pupil Detection and Eye Tracking System

This project implements a computer vision–based pupil detection system using facial landmark analysis.
The system detects eye regions from human face images and accurately localizes pupil centers.

---

## 📌 Overview

The system uses Dlib’s 68-point facial landmark detector to extract eye coordinates.
Dark pixel analysis and Hough Circle Transform are applied to identify pupil locations.
If circle detection fails, fallback logic is used to estimate pupil position.

---

## 🛠 Tech Stack
- Python
- OpenCV
- Dlib
- NumPy
- Image Processing
- Computer Vision

---

## 🚀 Features
- Face detection using frontal face detector
- 68-point facial landmark extraction
- Eye region localization using landmark indices
- Pupil detection using pixel-intensity analysis
- Circle detection using Hough Circle Transform
- Fallback logic for robust pupil localization
- Batch image processing with annotated outputs

---

## 🔄 Project Workflow
1. Detect face from input image
2. Extract 68 facial landmarks using Dlib
3. Crop left and right eye regions
4. Identify dark pixels corresponding to pupil
5. Apply Hough Circle Transform for pupil detection
6. Annotate and save output images

---


### Results

<img src="output/1.jpg" width = "300" height = "280"/> <img src="output/2.jpg" width = "300" height = "280"/>
<img src="output/3.jpg" width = "300" height = "280"/> <img src="output/4.jpg" width = "300" height = "280"/>

## 🎯 Applications

Eye tracking systems

Driver drowsiness detection

Online exam proctoring

Human–computer interaction

 ## ⚠️ Limitations

Sensitive to lighting conditions

Reduced accuracy with reflections or glasses

Slower performance for real-time video processing

🔮 Future Improvements

Replace Dlib with MediaPipe for faster landmark detection

CNN-based pupil segmentation

Real-time webcam support

Backend deployment using Flask or FastAPI


## Keywords

Pupil-detection, face-detection, eye-detection, opencv-image-processing, dlib, HoughCircles, artificial-intelligence, machine-learning, ai-ml
