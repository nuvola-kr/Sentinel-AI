# Sentinel-AI
An AI-driven software solution for automated labeling, quality control, and traceability of Intel SSD cards. Utilizes Python, TensorFlow, OpenCV, and SQLite to simulate defect detection, generate/validate labels, and log data, ensuring compliance with standards like RoHS. Ideal for manufacturing process enhancement.

**Overview**

Sentinel AI is an AI-driven software solution designed to enhance manufacturing processes by automating labeling, quality control, and traceability for Intel SSD cards. This project simulates defect detection, generates and validates labels with metadata (e.g., ISN, Capacity, RoHS Compliance), and logs data for audit purposes using Python-based AI techniques. It leverages open-source libraries to ensure compliance with standards like RoHS and supports manufacturing traceability.

**Features**

Defect Detection: Uses a Convolutional Neural Network (TensorFlow) to identify defects on SSD card surfaces (>90% accuracy).
Label Generation: Creates label images with QR codes and metadata using Pillow and qrcode.
Label Validation: Verifies label accuracy with OCR (EasyOCR).
Traceability: Logs inspection and labeling data in an SQLite database.
Simulation: Processes simulated SSD card images at 30-40 FPS.

**Requirements**

Python 3.8+

**Libraries:**

tensorflow
opencv-python
pillow
qrcode
easyocr
sqlite3

**Development Environment:** Google Colab or local setup with GPU support
