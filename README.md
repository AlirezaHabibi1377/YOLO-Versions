# YOLOv8 Object Detection and Segmentation Project

This repository contains code for object detection and segmentation using the YOLOv8 model. The project leverages Google Colab for training and inference tasks, with datasets managed via Roboflow.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Input and Output](#input-and-output)
- [Algorithms Used](#algorithms-used)

## Installation

To get started, clone the repository and install the necessary dependencies:

```python
# Mount Google Drive
from google.colab import drive
drive.mount('/content/gdrive')

# Set up the project directory
ROOT_DIR = '/content/gdrive/MyDrive/DL_projects_colab/yolov8/'
%cd {ROOT_DIR}

# Clone the Ultralytics repository
!git clone https://github.com/ultralytics/ultralytics.git

# Navigate to the cloned repository
%cd ultralytics

# Install the ultralytics package
!pip install ultralytics

# Install Ipython for displaying images
!pip install Ipython
