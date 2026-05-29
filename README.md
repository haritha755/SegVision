# SegVision — YOLOv8 Video Segmentation

SegVision is a real-time AI-powered video segmentation web application built using **YOLOv8**, **Flask**, **OpenCV**, and a modern interactive frontend.

The application allows users to upload videos, choose different YOLOv8 segmentation models, adjust confidence thresholds, and visualize segmented video streams directly in the browser.

---

# 🚀 Features

* 🎥 Drag-and-drop video upload
* 🤖 Multiple YOLOv8 segmentation model support
* ⚙️ Adjustable confidence threshold
* 📊 Real-time upload and processing progress tracking
* 🖥️ Modern responsive UI
* 🔴 Live segmentation stream visualization
* 🧠 Instance segmentation using YOLOv8
* 🛑 Stream control system (start/stop/reset)

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript

## Backend

* Flask
* Python

## AI / Computer Vision

* YOLOv8 Segmentation
* OpenCV
* Ultralytics

---

# 📂 Supported Models

| Model       | Description                     |
| ----------- | ------------------------------- |
| YOLOv8n-seg | Fastest, lightweight            |
| YOLOv8s-seg | Balanced speed and accuracy     |
| YOLOv8m-seg | Higher accuracy                 |
| YOLOv8x-seg | Best accuracy, slower inference |

---

# 📦 Installation

## 1. Clone the Repository

```bash id="b50k53"
git clone <repository-link>
cd <project-folder>
```

---

## 2. Install Dependencies

```bash id="tds4xj"
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash id="x2ig2x"
python app.py
```

Open in browser:

```text id="wmmd7m"
http://127.0.0.1:5000
```

---

# 📖 How It Works

1. User uploads a video through the frontend
2. Frontend sends video and settings to the Flask backend
3. YOLOv8 processes video frames for instance segmentation
4. OpenCV renders segmentation masks and detections
5. Processed frames are streamed back to the frontend in real time

---

# ⚙️ Features Explained

## Model Selection

Users can switch between different YOLOv8 segmentation models depending on:

* speed requirements
* hardware capability
* accuracy needs

---

## Confidence Threshold

Controls minimum confidence for detections.

* Higher threshold → fewer, more confident detections
* Lower threshold → more detections, possible false positives

---

## Live Stream System

Segmented frames are streamed continuously from the backend to the frontend using real-time video streaming.

---

# 💡 Beginner Tips

* Start with `YOLOv8n-seg` for faster testing
* Use shorter videos during development
* Lower confidence threshold if objects are missing
* GPU acceleration improves performance significantly

---

# ⚠️ Requirements

* Python 3.8+
* Minimum 4GB RAM
* GPU recommended (optional)

---

# 🧩 Future Improvements

* Real-time webcam segmentation
* Object tracking integration
* AI video summarization
* Detection analytics dashboard
* Download processed video
* Cloud deployment
* Multi-user support

---

# 📸 Screenshots

Add your project screenshots here.

---

# 📚 Learning Outcomes

This project helped explore:

* Real-time AI inference
* Computer vision pipelines
* YOLOv8 segmentation
* Video frame processing
* Flask backend development
* Frontend-backend communication
* Streaming architectures

---

# 👨‍💻 Author

Haritha A


