# Real-Time Detection Projects Using MediaPipe

## Objective
To implement real-time detection of facial landmarks, hand landmarks, and human poses using MediaPipe and OpenCV.

## Projects

### 1. Face Mesh Detection

**Description:**  
This project uses MediaPipe's Face Mesh solution to detect and visualize facial landmarks in real-time through a webcam feed. The model identifies key facial features and overlays a mesh on the detected face to highlight these features.

**Features:**
- Detects up to one face in real-time.
- Visualizes landmarks with a tesselation overlay.
- Displays the processed video feed with the detected landmarks.

**Usage:**
- Ensure you have a webcam connected.
- Run the script to start the video feed.
- The landmarks will be drawn on the detected face in real-time.
- Press 'q' to exit the video feed.

### 2. Hand Detection

**Description:**  
This project leverages MediaPipe's Hands solution to detect and visualize hand landmarks in real-time using a webcam feed. It identifies key points on the hands and draws connections between them to outline the hand's structure.

**Features:**
- Detects up to two hands in real-time.
- Visualizes landmarks with connection lines.
- Displays the processed video feed with the detected hand landmarks.

**Usage:**
- Ensure you have a webcam connected.
- Run the script to start the video feed.
- The landmarks will be drawn on the detected hands in real-time.
- Press 'q' to exit the video feed.

### 3. Pose Estimation

**Description:**  
This project uses MediaPipe's Pose solution to detect and visualize human poses in real-time via a webcam feed. The model identifies key body parts and draws connections to form a skeleton overlay on the person.

**Features:**
- Detects human pose landmarks in real-time.
- Visualizes landmarks with connection lines to form a skeleton.
- Displays the processed video feed with the detected pose landmarks.

**Usage:**
- Ensure you have a webcam connected.
- Run the script to start the video feed.
- The landmarks will be drawn on the detected poses in real-time.
- Press 'q' to exit the video feed.

## Installation

To run these projects, you'll need to install the following libraries:

```bash
pip install opencv-python mediapipe
