# Human Facial Expression Recognition (FER) Using Computer Vision

A deep learning-based computer vision application designed to detect human faces from image or video feeds and accurately classify their facial expressions into core emotional states.

Facial Expression Recognition (FER) plays a vital role in human-computer interaction, smart surveillance, and sentiment analysis. This project focuses on building a pipeline that can localize a human face within a frame and predict the corresponding emotion using Convolutional Neural Networks (CNNs).

The system is trained to recognize core facial expressions such as:
- 😊 Happy
- 😢 Sad
- 😡 Angry
- 😮 Surprise
- 😐 Neutral
- 😨 Fear 

## Tech Stack & Tools
- Programming Language: Python 3.x
- Computer Vision: OpenCV (for face detection and image preprocessing)
- Deep Learning Framework: TensorFlow / Keras 
- IDE / Environment: VS Code, Jupyter Notebook
- Version Control: Git & GitHub

##  Key Features
- Face Detection: Utilizes OpenCV's Haar Cascades (or MTCNN) to accurately detect and crop faces from the background.
- Real-time Processing: Capable of processing live webcam feeds to display emotion labels dynamically.
- Grayscale Normalization: Preprocesses input images by converting them to grayscale and resizing them (e.g., 48x48 pixels) to match the model's architecture.
- Probability Overlay: Displays the emotion label and confidence score directly above the detected face bounding box.

##  System Workflow
1. Input: Static Image, Video File, or Live Webcam Feed.
2. Face Detection: Bounding boxes are drawn around detected faces using OpenCV.
3. Preprocessing: The detected face region is cropped, converted to grayscale, and normalized.
4. Model Inference: The preprocessed face is passed into the trained CNN model.
5. Output Display: The predicted emotion label (e.g., "Happy - 92%") is rendered onto the output screen.

##  Project Visuals & Screenshots
Since the complete end-to-end source code is restricted, the screenshots below demonstrate the system's architecture and output capabilities achieved during development.

![Facial Expression Detection Output](happy.jpg)



Important Note: This repository contains the core system architecture, workflow documentation, and partial implementation files for this university project. Due to data migration and system loss, the full production codebase is currently unavailable. 

However, the logic, preprocessing pipelines, and model structures documented here accurately reflect the technical milestones achieved during this project's lifecycle.


