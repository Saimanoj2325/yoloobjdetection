# YOLO Object Detection

This project implements real-time object detection using the YOLO (You Only Look Once) model, specifically YOLOv5, to detect and classify objects in images and video streams. It includes both training and inference capabilities, with a structured data preprocessing pipeline to prepare datasets for YOLOv5.

## Features
- **YOLOv5 Model Integration**: Utilizes YOLOv5 for accurate, high-speed object detection.
- **Data Preprocessing**: Includes image resizing, annotation formatting, and dataset organization to ensure compatibility with YOLOv5.
- **Real-time Detection**: Capable of detecting objects in real-time from both images and video sources.

## Installation

1. **Clone the repository**:
   - git clone https://github.com/Saimanoj2325/yoloobjdetection.git
   - cd yoloobjdetection
2. **Install Dependencies**:
    Make sure you have Python 3.7+ installed, then install the required packages:
    pip install -r requirements.txt
3.**Configure the Dataset**:
   Edit the data.yaml file to define your dataset paths and class names.
   This file should include:
    - 1.train and val paths for training and validation datasets.
    - 2.names field listing the class names for your detection mode
# Data Preprocessing
The Yolov5Datapreprocessing.ipynb notebook guides you through preparing your dataset, resizing images, and formatting annotations for YOLOv5 compatibility.
# Project Structure
- 1.main.py: Main script to train and run inference using YOLOv5.
- 2.Yolov5Datapreprocessing.ipynb: Jupyter notebook for data preprocessing.
- 3.data.yaml: Configuration file specifying dataset paths and class names.
- 4.images/: Directory to store input images for testing.
- 5.output/: Directory where output images with detections will be saved.
