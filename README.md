# MultiPose Real-Time Human Pose Estimation

A real-time multi-person human pose estimation system built using **TensorFlow MoveNet Multipose (Lightning)** and **OpenCV**. This project detects and visualizes human keypoints and skeletal connections from both video files and live webcam streams with high efficiency and low latency.

---

## 📌 Project Overview

This project implements a **real-time multi-person pose estimation pipeline** capable of detecting multiple humans simultaneously and rendering **17 anatomical keypoints per person**.  
The system is optimized for speed and accuracy, making it suitable for real-world computer vision applications.

The architecture leverages a **MobileNetV2 image feature extractor**, combined with a **Feature Pyramid Network (FPN)** decoder and **CenterNet-style prediction heads**, enabling fast inference while maintaining robustness.

---

## 🧠 Model Architecture

- **Backbone:** MobileNetV2 (Depth Multiplier: 1.75)
- **Decoder:** Feature Pyramid Network (FPN) with stride 4
- **Prediction Head:** CenterNet-style keypoint detection
- **Model Variant:** MoveNet Multipose Lightning
- **Output Format:**  
  - 17 keypoints per person  
  - Each keypoint: *(x, y, confidence score)*  
  - Supports detection of up to 6 people per frame

---

## ⚙️ Key Features

- ✅ Real-time multi-person pose estimation
- ✅ Supports both video files and live webcam input
- ✅ Confidence-based keypoint filtering
- ✅ Skeletal connection rendering
- ✅ GPU acceleration support (optional)
- ✅ Modular OpenCV-based visualization pipeline
- ✅ Efficient inference suitable for real-time applications

---

## 🛠️ Technology Stack

- **Programming Language:** Python  
- **Deep Learning Framework:** TensorFlow, TensorFlow Hub  
- **Computer Vision:** OpenCV  
- **Numerical Computing:** NumPy  
- **Visualization:** OpenCV drawing utilities  
- **Hardware Acceleration:** GPU (optional)

---

## 🎥 Input Sources

- Pre-recorded video files (MP4)
- Live webcam stream for real-time pose estimation

---

## 📈 Use Cases

- Human activity recognition
- Sports performance analysis
- Gesture recognition systems
- Surveillance and crowd analysis
- Human–Computer Interaction (HCI)
- AI-assisted fitness and posture monitoring

---

## 🚀 Learning Outcomes

- Hands-on experience with **state-of-the-art pose estimation models**
- Real-time deep learning inference pipeline design
- Integration of deep learning models with OpenCV
- Confidence-based post-processing and visualization
- Practical exposure to multi-person detection challenges

## 📌 Notes

- The project includes both video-based and webcam-based inference pipelines.
- GPU usage is optional and automatically configured when available.
- Confidence thresholds can be adjusted to tune detection accuracy.

## 🧑‍💻 From Author

Developed as part of an AI/ML-focused computer vision project to demonstrate real-time deep learning inference, multi-person pose estimation, and applied computer vision engineering.
