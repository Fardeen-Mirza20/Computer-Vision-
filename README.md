# Real-Time Face Detection using OpenCV

## 📌 Overview

This project implements a **real-time face detection system** using OpenCV. It captures live video from a webcam, processes each frame, and detects human faces using a pre-trained Haar Cascade classifier. Detected faces are highlighted with bounding boxes in real time.

---

## 🚀 Features

* Real-time face detection via webcam
* Uses Haar Cascade Classifier for efficient detection
* Lightweight and fast (low computational cost)
* Simple and easy-to-understand implementation

---

## 🛠️ Tech Stack

* Python
* OpenCV

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/face-detection-opencv.git
cd face-detection-opencv
```

2. Install dependencies:

```bash
pip install opencv-python
```

3. Download Haar Cascade file:

* Download `haarcascade_frontalface_default.xml` from OpenCV GitHub
* Place it in your project directory

---

## ▶️ Usage

Run the script:

```bash
python face_detection.py
```

* Press **ESC (Esc key)** to exit the application.

---

## 📷 How It Works

* Captures video using webcam (`cv2.VideoCapture(0)`)
* Converts frames to grayscale for faster processing
* Detects faces using `detectMultiScale()`
* Draws rectangles around detected faces
* Displays output in real time

---

## 📊 Results

* Successfully detects faces in real-time video streams
* Performs efficiently on standard hardware
* Works well under normal lighting conditions

---

## 🔮 Future Improvements

* Add deep learning-based models (e.g., DNN, MTCNN, YOLO) for higher accuracy
* Implement face recognition (identity detection)
* Optimize performance for edge devices
* Add support for image and video file input

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.
