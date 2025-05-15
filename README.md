# 😴 Real-Time Drowsiness Detection using CNN

This project uses **Convolutional Neural Networks (CNN)** and **OpenCV** to monitor a driver’s eyes in real-time and trigger an alert if drowsiness is detected. If the eyes remain closed for 10 seconds continuously, a **beep alarm** sounds to wake the driver and prevent potential accidents.

---

## 📌 Project Objective

The main objective is to build an intelligent real-time system that:
- Monitors eye state (open or closed) using a webcam.
- Uses a trained CNN model for eye classification.
- Triggers an audio alarm if the driver's eyes are closed for more than 10 seconds.

---

## 🚀 Features

- 👁️ Real-time eye state detection (open/closed)
- 🧠 CNN-based classification model
- ⏱️ 10-second threshold-based alert system
- 🔊 Beep alarm sound for drowsiness alert
- 🖥️ Works with webcam for live monitoring

---

## 🛠️ Tech Stack

- Python 🐍
- OpenCV 📷
- TensorFlow / Keras (for CNN) 🧠
- Google Colab (development environment) 💻
- NumPy

---

## 🧠 Model Overview

- **Model Type:** Convolutional Neural Network (CNN)
- **Input:** Eye region images (grayscale)
- **Output:** Binary classification – Open (0) or Closed (1)
- **Training Data:** Eye state dataset (custom or open dataset like `mrlEyeDataset`)
- **Performance:** High accuracy on test set with real-time inference

---

## 🖼️ Demo Screenshot

![Dashboard Preview](./open eyes.png)
![Dashboard Preview](./closed eyes.png)
---


---

## 🔄 How It Works

1. Webcam captures real-time video.
2. Face and eyes are detected using OpenCV.
3. Each eye image is fed into the trained CNN.
4. If both eyes are closed:
   - A timer starts.
   - If closed for ≥10 seconds → Alarm sounds.
   - If eyes open → Timer resets.

---

## 📦 Installation

You can run this project on Google Colab or locally:

### ▶️ On Google Colab:
- Upload the notebook and required files.
- Run all cells.

---

📊 Results

- Model Accuracy: 92%
- Drowsiness Detection Delay: <1s real-time
- Use Case: Vehicle driver alertness monitoring

---

🙋‍♀️ Author
- Dhanushi
- B.Tech CSE | ML Enthusiast | [LinkedIn](https://www.linkedin.com/in/dhanushi-gupta-b3b397215/)






