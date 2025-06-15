# Vehicle Classification using YOLOv8 🚗🚓🚚

This project implements a deep learning model using **YOLOv8** to detect and classify various types of vehicles such as **SUVs, hatchbacks, sedans, ambulances, pickups, and more** from images and video streams.

## 📌 Overview

The goal of this project is to build a robust vehicle classification system that can:
- Detect vehicles in real-time
- Classify them into multiple categories
- Work on both images and live video streams

The model leverages **Ultralytics' YOLOv8**, known for its speed and accuracy in object detection tasks.

---

## 🧠 Model Details

- **Architecture**: YOLOv8 (You Only Look Once - version 8)
- **Framework**: PyTorch (via Ultralytics YOLO)
- **Classes Detected**: 
  - Sedan
  - SUV
  - Hatchback
  - Ambulance
  - Pickup truck
  - Others (expandable)

---

## 📁 Dataset

- The dataset used consists of labeled images containing vehicles from multiple angles and environments.
- Annotated in YOLO format (bounding boxes + class IDs).
- Custom classes trained via transfer learning on YOLOv8.

---

## 🚀 Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/Shubham281103/Vehicle_Classifier.git
   cd Vehicle_Classifier
