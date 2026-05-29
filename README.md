# Real-Time Object Detection and Tracking using YOLOv8

## Project Overview

This project implements a real-time object detection and multi-object tracking system using YOLOv8 and ByteTrack. The system detects objects such as persons, cars, buses, trucks, motorcycles, and bicycles from video streams and assigns unique tracking IDs to monitor their movement across frames.

The model is pretrained on the COCO dataset and is designed for intelligent monitoring and surveillance applications.

---

## Domain

Security, Vision AI

---

## Model Used

* YOLOv8 (Object Detection)
* ByteTrack (Multi-Object Tracking)

---

## Dataset

COCO (Common Objects in Context) Dataset

* 80 object categories
* Large-scale benchmark dataset
* Supports person, vehicle, and everyday object detection

---

## Features

* Real-time object detection
* Multi-object tracking
* Unique ID assignment
* Bounding box visualization
* GPU acceleration using Google Colab T4
* Video processing and result generation

---

## Project Workflow

Video Input
↓
Frame Extraction
↓
YOLOv8 Object Detection
↓
Bounding Box Generation
↓
ByteTrack Tracking
↓
Object ID Assignment
↓
Output Visualization

---

## Technologies Used

* Python
* OpenCV
* Ultralytics YOLOv8
* ByteTrack
* Google Colab
* NumPy

---

## Installation

```bash
pip install ultralytics opencv-python supervision
```

## Run the Project

```bash
python yolov8_tracking.py
```

---

## Applications

* Smart Surveillance Systems
* CCTV Monitoring
* Traffic Monitoring
* Intelligent Transportation Systems
* Smart Cities
* Security Analytics

---

## Results

The system successfully detects and tracks multiple objects in real time. Each detected object is assigned a unique ID and tracked continuously across video frames, making it suitable for intelligent monitoring environments.

---

## Future Improvements

* Face Recognition Integration
* Crowd Analysis
* Vehicle Counting
* Intrusion Detection
* Suspicious Activity Monitoring

---

## Author

Jay Prakash

M.Tech Artificial Intelligence

Dr. B.R. Ambedkar National Institute of Technology (NIT) Jalandhar

---

## License

MIT License
