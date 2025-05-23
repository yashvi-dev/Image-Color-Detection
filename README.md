# 🎨 RGB Color Detection from Image & Webcam using OpenCV

This project is a beginner-friendly computer vision tool built using **Python** and **OpenCV**. It detects the RGB (Red, Green, Blue) color values from:

- 📸 A static image (by clicking on any pixel)
- 🎥 A live webcam feed (real-time detection using mouse position)

Ideal for learning OpenCV basics, this project also demonstrates color recognition logic and interactive feedback using OpenCV GUIs.

---

## 🚀 Features

- Detect RGB color values from any pixel in an image
- Real-time RGB color detection from a webcam feed
- Displays color block and RGB values on screen
- Built in **Jupyter Notebook** – beginner friendly!

---

## 🧠 How It Works

### 📷 Image Mode
- Load an image with `cv2.imread()`
- Register a mouse click using OpenCV's event handler
- Get pixel value using NumPy indexing
- Show the RGB values on click

### 🎥 Webcam Mode
- Capture live feed with `cv2.VideoCapture(0)`
- Get the current mouse position
- Read the pixel color under the cursor every frame
- Display color and RGB values live

---

## 📸 Demo

### ✅ Color Detection from Image

> Click on any pixel in the image to detect its RGB color.

![RGB Detection from Image](images/rgb_from_image.png)

---

### ✅ Real-Time RGB Detection from Webcam

> Hover your mouse over any part of the video to get RGB color in real-time.

![RGB Detection from Webcam](images/rgb_from_webcam.png)

---

## 📦 Installation
### 1. Clone this repository

```bash
git clone https://github.com/yashvi-dev/Image-Color-Detection.git
cd Image-Color-Detection

```
## 2. Install required packages

```bash
pip install opencv-python numpy

```
