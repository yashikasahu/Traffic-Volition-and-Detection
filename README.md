<h1>Traffic Violation Detection System</h1>

AI-Powered Real-Time Helmet Detection, Triple Riding Detection & Road Safety Monitoring

An advanced computer vision system built using YOLO / Deep Learning to automatically detect common road violations such as no-helmet, helmet violation for pillion rider, triple riding, and motorcycle detection.

<h1>🚀 Project Highlights</h1>

Detects Helmet Violations (driver + pillion)

Detects Triple Riding

Detects Motorcycle Classification

Works on images, videos, and real-time CCTV feeds

High accuracy with YOLO-based object detection

Auto-identifies multiple violations in the same frame

Outputs bounding boxes + class labels + confidence scores

Can integrate with traffic police alert systems

<h1>📸 Detection Examples</h1>
<h3>1. Helmet Violation Detection</h3>
<img width="303" height="297" alt="Screenshot 2025-05-11 173908" src="https://github.com/user-attachments/assets/16f5dfde-3662-494d-a75f-9b554c36d633" />


<h3>2. Triple Riding Detection</h3>
<img width="602" height="590" alt="Screenshot 2025-05-11 174026" src="https://github.com/user-attachments/assets/b13d1db0-0b1d-4167-a2a6-d3b7fe33d7d0" />


<h3>3. Multiple Violations in One Frame</h3>
<img width="844" height="585" alt="Screenshot 2025-05-11 174534" src="https://github.com/user-attachments/assets/214ce8cf-741c-4cf6-8df2-03259835f7e1" />


<h3>4. Real-Time Violation Capture
<img width="529" height="303" alt="Screenshot 2025-05-11 173220" src="https://github.com/user-attachments/assets/547c7826-7860-4fbe-b6d6-f8950444cb5f" />

<h1>🧠 How It Works</h1>

1. Model

The system uses a YOLO-based deep learning model trained on:

Helmet vs no helmet

Person detection

Motorcycle detection

Triple-riding patterns

2. Pipeline

Frame extraction from video or CCTV

YOLO detection

Bounding box generation

Violation classification

Output screenshot / video with labels

<h1>🔧 Tech Stack</h1>

Python

OpenCV

YOLOv5 / YOLOv8

torch

NumPy

Deep Learning

Image annotation tools (Roboflow)

<h1>📊 Results</h1>

Helmet Detection Accuracy: 95%+

Triple Riding Detection: 85%+

Multi-violation detection supported

Works on low-light frames
