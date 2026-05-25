# Face Recognition System using OpenCV

## Overview

This project is a real-time Face Recognition System built using Python and OpenCV. It captures face images, trains a recognition model, and recognizes faces through a webcam in real time.

---

# Technologies Used

* Python
* OpenCV
* Haar Cascade Classifier
* LBPH Face Recognizer

---

# Project Directory Structure

```text id="isfjc7"
face_recognition/
│
├── create_data.py
├── face_recognize.py
├── datasets/
│   └── varadhu/
│       ├── 1.png
│       ├── 2.png
│       ├── 3.png
│       ├── 4.png
│       └── ...
│
└── README.md
```

---

# Installation

Install OpenCV:

```bash id="j7g8eb"
pip install opencv-contrib-python
```

---

# Step 1 — Create Dataset

Run:

```bash id="w6oyx4"
python create_data.py
```

This will:

* Open the webcam
* Detect faces
* Capture face images automatically
* Store images inside the `datasets` folder

Press `ESC` to exit.

---

# Step 2 — Run Face Recognition

Run:

```bash id="2rd8z9"
python face_recognize.py
```

This will:

* Load dataset images
* Train the face recognition model
* Start real-time face recognition using webcam

Press `ESC` to exit.

---

# Features

* Real-time face detection
* Automatic dataset creation
* Face recognition using LBPH
* Webcam-based recognition
* Multiple face dataset support

---

# Dataset Example

```text id="pov1ju"
datasets/
│
├── varadhu/
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   └── ...
│
├── person2/
│   ├── 1.png
│   ├── 2.png
│   └── ...
```

---

# Future Enhancements

* Attendance System
* GUI Interface
* Database Integration
* Deep Learning Face Recognition
* Anti-Spoofing Detection

---

# Author

**Varadha Rajan S**
