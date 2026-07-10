# Color Recognition with OpenCV

A computer vision project that demonstrates real-time color recognition using **Python** and **OpenCV**. The project includes an interactive HSV color selector and a webcam-based color detection system capable of identifying common colors in real time.

---

## Project Overview

This project demonstrates how computer vision techniques can be used to recognize colors from a live webcam feed. It includes two Python applications:

- **HSV.py** – An interactive tool for exploring HSV color values using adjustable trackbars.
- **c_detection.py** – A real-time application that captures video from a webcam and detects the color at the center of the frame.

The project provides practical experience with image processing, the HSV color space, and real-time computer vision using OpenCV.

---

## Features

- Real-time HSV color selection using interactive trackbars
- Live webcam-based color detection
- Recognition of common colors:
  - Red
  - Orange
  - Yellow
  - Green
  - Blue
  - Purple
  - Pink
  - Gray
  - White
  - Black
- Displays the detected color name in real time
- Uses the HSV color space for accurate color recognition
- Lightweight implementation using OpenCV and NumPy

---

## Technologies Used

- Python
- OpenCV
- NumPy

---

## Installation

Install the required packages:

```bash
pip install opencv-python numpy
```

---

## Usage

### 1. HSV Color Selector

Run:

```bash
python HSV.py
```

**Controls**

- Adjust **Hue (H)**, **Saturation (S)**, and **Value (V)** using the trackbars.
- The selected color updates instantly.
- Press **Esc** to exit.

---

### 2. Real-Time Color Detection

Run:

```bash
python c_detection.py
```

**How it works**

- Captures live video from the webcam.
- Converts each frame to the HSV color space.
- Samples the center pixel.
- Displays the detected color name in real time.
- Press **Esc** to exit.

---

## Example Outputs

### HSV Color Selector

![HSV Color Selector](https://github.com/user-attachments/assets/dd37235d-6f79-41c5-887b-3cd14e7462d3)

### Real-Time Color Detection

![Real-Time Color Detection](https://github.com/user-attachments/assets/80fe5a13-a4a8-4cb7-8449-a86cba7cb09f)

---


## Learning Outcomes

Through this project, I gained practical experience in:

- Computer Vision using OpenCV
- Image processing techniques
- HSV color space
- Real-time webcam applications
- Interactive GUI development with OpenCV trackbars
- Python programming for computer vision

