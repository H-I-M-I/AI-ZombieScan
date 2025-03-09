# Zombie Detection using TensorFlow Object Detection API

This project implements an **object detection model** to detect zombies in images or video streams using TensorFlow's Object Detection API. The code utilizes pre-trained models and TensorFlow utilities to identify and classify zombies effectively.

## Design and Architecture
- **Framework**: Built using **TensorFlow 2.x** and the **Object Detection API**.
- **Model**: Uses pre-trained models from TensorFlow’s Model Zoo, allowing fine-tuning for improved zombie detection.
- **Data Handling**: Images are loaded and converted into NumPy arrays for TensorFlow processing.
- **Visualization**: Detection results are displayed using Matplotlib with bounding boxes and class labels.

## Supported Models
This project supports various object detection models, including:
- **SSD MobileNet V2** (Fast but less accurate)
- **Faster R-CNN** (More accurate but slower)
- **EfficientDet** (Balanced between speed and accuracy)

## How It Works
1. **Environment Setup**: The TensorFlow Model Garden is cloned, and dependencies are installed.
2. **Model Initialization**: A pre-trained model is loaded from a checkpoint and configured using a pipeline file.
3. **Image Processing**: The input image is converted into a NumPy array for TensorFlow inference.
4. **Inference**: The model predicts bounding boxes, class labels, and confidence scores.
5. **Visualization**: The detected objects are drawn on the image using TensorFlow’s visualization utilities.

## Potential Use Cases
- **Gaming & Augmented Reality**: Detect and track zombies in AR-based applications.
- **Security & Surveillance**: Monitor unusual activities in real-time video streams.
- **Film & Entertainment**: Automate visual effects in horror-themed projects.
