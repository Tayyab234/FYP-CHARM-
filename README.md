# FYP-CHARM-
 CHARM – Chicken Health Assessment through Real-time Monitoring
🔍 Project Overview
The CHARM project is a deep learning-based poultry health monitoring system designed to detect, track, and classify diseases in chickens using computer vision. This Jupyter Notebook demonstrates the core functionality of the CHARM pipeline, which integrates object detection, tracking, and multithreaded disease classification using multiple neural network models.

The system uses:

YOLOv11 Models for full-body and neck-region detection.

BoT-SORT Algorithm for multi-object tracking to maintain chicken identities across frames.

ResNet50 Classifiers for both general and specific disease categorization.

Multithreading to process detections and classifications concurrently, enabling real-time performance.

The notebook processes videos/images to detect chickens, track their movement, classify health status, and output annotated media with color-coded bounding boxes (green for healthy, orange for Marek’s, red for other diseases). The system is optimized for real poultry farm conditions, handling clutter, variable lighting, and occlusions.

📂 Files Included
FYP(CHARM).ipynb: The main Jupyter Notebook containing the detection, tracking, and classification code.

Pre-trained YOLOv11 models for full-body and neck detection.

Pre-trained ResNet50 models for full-body and neck-based classification.

Supporting utility functions for quality assessment, threading, and visualization.

🚀 Key Features
🐔 Full-body and neck detection using YOLOv11

🔄 Multi-object tracking with BoT-SORT

🩺 Real-time disease classification (general and specific)

🎯 Quality-based reclassification to improve accuracy

🌐 Scalable design suitable for real-time web or local deployment

🛠️ Technologies Used
. Python

. OpenCV

. PyTorch

. YOLOv8

. ResNet50

. BoT-SORT Tracking

. Jupyter Notebook

▶️ How to Run
Clone the repository or download the notebook.

Ensure the following dependencies are installed:

bash
pip install opencv-python torch torchvision yolov5
Place the required pre-trained models in the designated paths inside the notebook.

Run the notebook cell by cell, following the order.

Upload a video or use the webcam to process real-time detection and classification.
