# 🚦 Smart Traffic Detection & Congestion Classification using YOLO

## 📌 Project Title
**Smart Traffic Monitoring System Using YOLO and Real-Time Video Analysis**

---

## 🧠 Problem Statement

Traditional traffic systems struggle with dynamic congestion patterns, limited human monitoring, and inefficient flow control. This project addresses the problem by creating an automated vision-based system that can:

- Detect and count vehicles in each lane.
- Evaluate congestion levels in real-time.
- Label traffic status as **Smooth** or **Heavy**.

---

## 🎯 Objectives

- Detect vehicles in traffic video using YOLOv8.
- Count vehicles lane-wise.
- Display traffic status dynamically based on vehicle count thresholds.
- Ensure scalability for real-time smart city applications.

---

## 🛠️ Tech Stack

| Component         | Tool / Framework       |
|------------------|------------------------|
| Language          | Python                 |
| Object Detection  | YOLOv8 (Ultralytics)   |
| Video Processing  | OpenCV                 |
| Deep Learning     | PyTorch                |
| Development       | Google Colab           |
| Deployment Ready  | Flask (optional)       |

---

## 📽️ System Workflow

1. 🎥 **Video Input**: Takes traffic video feed.
2. 🔲 **Lane Segmentation**: Define bounding boxes for lanes.
3. 🛻 **Vehicle Detection**: YOLOv8 detects vehicles in each lane.
4. 🔢 **Counting Logic**: If a vehicle enters a lane box, it is counted.
5. 🚦 **Traffic Status**: 
   - `Vehicle Count > 10`: **Heavy**
   - `Vehicle Count ≤ 10`: **Smooth**
6. 🖼️ **Display**: Video shows bounding boxes, count, and traffic label.

---

## 📊 Output Features

- Vehicle bounding boxes
- Lane-specific counts
- Traffic status overlay (Smooth / Heavy)
- Live feed support for real-time deployment

---

