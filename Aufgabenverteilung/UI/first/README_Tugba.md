🖼️ UI – User Interface (Qt)
🎯 Goal
Develop a user interface using Qt that displays the webcam stream, shows personalized messages when a known user is detected, and provides a settings panel to define/edit user profiles.

📋 Tasks
1. Research (Days 1–4)
Learn how to install and set up Qt Creator.

Understand the following Qt components:

QMainWindow, QLabel, QPushButton, QLineEdit, QTimer, QJsonDocument

Learn how to:

Convert cv::Mat to QImage.

Display the converted image on a QLabel.

Read and write JSON files in Qt.

2. Implementation (Days 5–14)
Capture webcam feed with OpenCV and display it inside a QLabel.

Overlay custom messages (e.g., “Welcome, Barış”) when a user is recognized.

Create a basic user settings panel:

Enter user name and personalized message.

Save data to user_config.json.

Implement a timer that refreshes the image and updates the UI accordingly.

📚 Resources
Qt for Beginners

Using OpenCV with Qt

Qt JSON Read/Write Docs

✅ Deliverables
A Qt GUI application that shows webcam stream in real time.

Shows personalized messages from JSON data.

Allows user profile/message creation via a simple form.