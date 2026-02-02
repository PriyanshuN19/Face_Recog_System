# 👤 Real-Time Face Recognition using OpenCV & KNN

A real-time face recognition system built using **Python**, **OpenCV**, and a **K-Nearest Neighbors (KNN)** classifier.  
The project captures face data through a webcam, trains a simple ML model, and recognizes known faces live.

---

## 🚀 Features

- 📸 Face data collection using webcam
- 🧠 Face recognition using KNN classifier
- 🖼️ Haar Cascade based face detection
- ⚡ Real-time prediction with live video feed
- 🧪 Lightweight & beginner-friendly ML pipeline

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** OpenCV, NumPy  
- **Algorithm:** K-Nearest Neighbors (KNN)  
- **Computer Vision:** Haar Cascade Classifier  

---
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/face-recognition-opencv.git
cd face-recognition-opencv
````

### 2️⃣ Install dependencies

```bash
pip install opencv-python numpy
```

---

## ▶️ How to Run

### 🔹 Step 1: Collect Face Data

```bash
python faceSaver.py
```

* Enter your name when prompted
* Face the camera with proper lighting
* Press **`q`** to stop after collecting samples

---

### 🔹 Step 2: Run Face Recognition

```bash
python faceRecog.py
```

* The system will detect and recognize known faces in real-time
* Press **`q`** to exit

---

## 🧠 How It Works

1. **Face Detection**
   Uses Haar Cascade to detect faces from webcam frames.

2. **Data Collection**
   Extracted face regions are resized and stored as flattened vectors.

3. **Training**
   A custom KNN classifier is trained on stored face vectors.

4. **Prediction**
   Live face frames are compared against stored data to identify the person.

---

## ⚠️ Notes

* Ensure good lighting for better detection accuracy
* `data/` directory is ignored to protect personal face data
* Works best for frontal face images

---

## 📌 Future Improvements

* Use Face Embeddings (FaceNet / Dlib)
* Improve accuracy with SVM or CNN
* Add GUI for better user experience
* Store data securely with encryption

---

## 👨‍💻 Author

**Priyanshu Nailwal**
Computer Science & AI Enthusiast

---

⭐ If you found this project helpful, feel free to star the repository!

```
