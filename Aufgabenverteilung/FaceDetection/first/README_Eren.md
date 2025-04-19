🟨 FACE DETECTION – Face Location
🎯 Goal
Develop a C++ module that detects all visible faces in the webcam feed and returns their coordinates. Provide cropped face images for further use.

📋 Tasks
1. Research (Days 1–4)
Study face detection methods in OpenCV:

Haar Cascades

DNN face detector (deploy.prototxt + .caffemodel)

Learn how to:

Use cv::VideoCapture for webcam feed

Detect faces using cv::CascadeClassifier or DNN

Extract and crop face regions

2. Implementation (Days 5–14)
Capture real-time webcam feed with OpenCV.

Apply face detection on each frame.

Draw bounding boxes around detected faces.

Crop faces and save them as images (optional).

Export coordinates of each detected face:

json
Kopyala
Düzenle
{ "x": 120, "y": 80, "width": 100, "height": 100 }
📚 Resources
OpenCV Haar Cascades Tutorial

OpenCV DNN Face Detector

OpenCV C++ VideoCapture

✅ Deliverables
Real-time face detection application in C++.

Bounding boxes shown on live webcam feed.

Optional: cropped face images + coordinate data saved to file.