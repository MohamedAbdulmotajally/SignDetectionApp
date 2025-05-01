# Traffic Sign Detection App

## Overview

This project is a real-time traffic sign detection system using OpenCV and a pre-trained deep learning model (Keras). The application captures video from a webcam, processes each frame to detect and classify traffic signs, and displays the results with bounding boxes and classification labels.

## Features

- 🧠 Deep learning-based classification using TensorFlow/Keras
- 📷 Real-time video processing with OpenCV
- 🛑 Detection of 43 different traffic sign classes
- 🎯 Probability thresholding to ensure prediction confidence
- ⚙️ HSV color-based segmentation for improved detection

## Installation

### Prerequisites

- Python 3.x
- pip

### Dependencies

Install the required packages using pip:

```bash
pip install numpy opencv-python tensorflow
