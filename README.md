# Shape Detector

The **Shape Detector** is an innovative computer vision application developed using **OpenCV 3.4.4**. It detects and classifies hand-drawn geometric shapes, such as **triangles, rectangles, pentagons, and circles**, from images or real-time webcam feeds. This project demonstrates the power of **image processing and contour detection**, making it useful for educational purposes and computer vision demonstrations.

---

## Features
- **Supports Multiple Shapes**: Recognizes triangles, rectangles, pentagons, and circles.
- **Input Options**:  
  1. **Image File**: Detect shapes from an image.  
  2. **Webcam Feed**: Real-time shape detection using your webcam.
- **Annotated Output**: Detected shapes are labelled directly on the image.
- **Image Preprocessing**: Converts images to grayscale, applies binary thresholding, and detects contours for shape classification.

---

## Demo

**Shape Detection in Action**  
<img src="assets/sample.gif" width="400px">

**Backend Process**  
<img src="assets/backend_video.png" width="400px">

---

## Prerequisites
Make sure you have the following installed:

- **Python 3.x**
- **OpenCV 3.4.4**  
  Install OpenCV using the command:
  ```bash
  pip install opencv-python==3.4.4
