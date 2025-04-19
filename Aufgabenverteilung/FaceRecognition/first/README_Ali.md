🧠 FACE RECOGNITION – Identity Matching
🎯 Goal
Build a system that identifies known faces using embeddings and a local face database. Match input faces with stored embeddings and return user identity.

📋 Tasks
1. Research (Days 1–4)
Understand the concept of face embeddings and similarity comparison.

Study Dlib face recognition pipeline:

Shape predictor

Embedding model (face_recognition_model_v1.dat)

Learn how to compare face embeddings:

Cosine similarity

Euclidean distance

Explore file storage formats: JSON, CSV

2. Implementation (Days 5–14)
Use sample face images (cropped manually or from detection module).

Extract 128-d face embeddings using Dlib.

Build a local face database:

Each entry contains: user ID, name, embedding vector

Compare new face embeddings with stored ones.

If a match is found → return user info

Else → return “Unknown”

Create a function:

cpp
Kopyala
Düzenle
std::string recognizeFace(cv::Mat faceImage);
📚 Resources
Dlib Face Recognition Tutorial

Dlib Model Files

Similarity Calculation in C++

✅ Deliverables
Face recognition function that returns identity or "unknown".

Local face database in JSON or CSV.

Command-line or test script to verify recognition.