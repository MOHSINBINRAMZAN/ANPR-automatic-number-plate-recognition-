**Automatic Number Plate Recognition (ANPR) using YOLOv8**
This project implements an Automatic Number Plate Recognition (ANPR) system using the state-of-the-art YOLOv8 (You Only Look Once, version 8) object detection model. ANPR systems are critical for applications such as toll collection, traffic law enforcement, and vehicle access control.

**Features**
**Real-Time Detection**: Utilizes YOLOv8 for real-time detection of number plates from video streams or images.
**High Accuracy:** Leveraging the latest advancements in the YOLO model for improved accuracy and performance.
**Flexible Input Sources:** Supports both static images and live video streams as input.
**Easy Integration:** Modular code design allows for easy integration into existing systems or further development.
**Cross-Platform:** Developed using Python, making it compatible with various operating systems.
**Project Structure**
**data/:** Directory containing sample images and videos for testing.
**models/:** Pre-trained YOLOv8 models and configuration files.
**src/**: Source code for ANPR system, including:
**detection.py:** Script for number plate detection.
**recognition.py:** Script for number plate recognition (character extraction).
**utils.py:** Utility functions for image processing and data handling.
**notebooks/:** Jupyter notebooks for experimenting with the model and visualizing results.
**requirements.txt**: List of required Python packages.
**Future Work**
**Enhanced Recognition**: Integrate advanced OCR (Optical Character Recognition) techniques for improved number plate reading.
**Dataset Expansion:** Expand the training dataset to include a wider variety of number plates from different regions.
**Performance Optimization:** Optimize the detection pipeline for faster processing on resource-constrained devices.
**Contributing**
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
