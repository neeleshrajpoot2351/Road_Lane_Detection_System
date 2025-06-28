# Min_Project_Sem3
Author - Neelesh Rajpoot
<br>
Date - 6/18/2024

# 🛣️ Lane Detection System using OpenCV

This is a Python-based lane detection project that uses OpenCV to detect road lanes from a video input. It performs edge detection, region masking, and line detection using the Hough Transform, and displays the lane lines on the video frames.

## 🚀 Features

- Real-time lane detection from video
- Uses Canny edge detection and Hough Line Transform
- Easy to understand and modify for beginners
- One-file Python script for simplicity

---

## 🧪 Technologies Used

- Python 3
- OpenCV (cv2)

---

## 📝 How It Works

1. Convert video frames to grayscale.
2. Apply Gaussian blur to reduce noise.
3. Use Canny Edge Detection to highlight edges.
4. Mask the region of interest (typically the road).
5. Use Hough Transform to detect lane lines.
6. Overlay the lane lines back on the video.

---

## 🖥️ Run the Project

### 🔧 Requirements

Install the required libraries:

```bash
pip install opencv-python



