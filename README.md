# Facial Emotion Recognition using OpenCV and DeepFace

## Overview

This project implements a **real-time facial emotion recognition system** using a webcam feed. It combines classical computer vision techniques from **OpenCV** with **DeepFace**, a deep learning–based facial analysis framework, to detect human faces and classify their emotions in real time.

The system is suitable for academic demonstrations, human–computer interaction experiments, and introductory applied AI projects.

---

## Key Features

* Real-time face detection using Haar Cascade classifiers
* Emotion classification using DeepFace pre-trained deep learning models
* Live webcam video stream processing
* Lightweight implementation with minimal setup
* Modular and easy-to-extend Python codebase

---

## Technology Stack

### Programming Language

* Python 3.8+

### Libraries & Frameworks

* OpenCV (cv2)
* DeepFace
* NumPy
* TensorFlow / Keras (via DeepFace backend)

---

## Project Structure

```
Facial-Emotion-Recognition-using-OpenCV-and-Deepface-main/
│
├── emotion.py
├── haarcascade_frontalface_default.xml
├── requirements.txt
```

---

## How It Works

1. The webcam captures real-time video frames.
2. OpenCV detects faces using a Haar Cascade classifier.
3. Each detected face is passed to DeepFace.
4. DeepFace predicts the dominant facial emotion.
5. The detected emotion label is rendered on the video stream.

---

## Installation & Setup

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd Facial-Emotion-Recognition-using-OpenCV-and-Deepface-main
```

### Step 2: Create and Activate Virtual Environment (Recommended)

```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Application

```bash
python emotion.py
```

* Ensure your webcam is connected and accessible.
* Press **`q`** to exit the application window.

---

## Output

* Bounding boxes around detected faces
* Real-time emotion labels such as:

  * Happy
  * Sad
  * Angry
  * Surprise
  * Neutral
  * Fear
  * Disgust

---

## Use Cases

* Human–Computer Interaction (HCI) experiments
* Emotion-aware recommendation systems
* AI-based user behavior analysis
* Educational demos for computer vision and deep learning

---

## Limitations

* Performance depends on lighting conditions and camera quality
* Pre-trained models may show bias across demographics
* Not optimized for large-scale or production environments

---

## Future Improvements

* Use CNN-based face detectors (e.g., DNN, MTCNN)
* Add emotion confidence scores
* Support video file input
* Improve FPS using multi-threading
* Deploy as a web or desktop application

---

## Author

Developed as an applied computer vision and deep learning project for academic and learning purposes.

---

## Acknowledgements

* OpenCV community
* DeepFace library contributors
* Haar Cascade models by OpenCV
