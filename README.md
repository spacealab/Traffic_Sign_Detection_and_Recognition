# Traffic Sign Detection and Recognition

This project focuses on real-time traffic sign detection and recognition using the YOLO (You Only Look Once) object detection model. It provides an end-to-end pipeline from dataset preparation to model training and inference.

## Features
- **Dataset Conversion**: Converts COCO annotations to YOLO format seamlessly.
- **Model Training**: Fine-tunes a pretrained YOLO model for custom traffic sign detection.
- **Inference**: Evaluates images, draws bounding boxes, and saves the annotated results to a dedicated directory.
- **Structured Code**: Clean, modular code with integrated error handling.

## Prerequisites
- Python 3.10+ (Tested on Python 3.12)
- Git

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/spacealab/Traffic_Sign_Detection_and_Recognition.git
   cd Traffic_Sign_Detection_and_Recognition
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv .venv
   
   # On Linux/macOS
   source .venv/bin/activate
   
   # On Windows
   .venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install ultralytics torch torchvision opencv-python jupyter
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Traffic_Sign_Detection_and_Recognition.ipynb
   ```

2. Run the cells sequentially:
   - **Data Preparation**: Formats the images and labels.
   - **Training**: Trains on the processed dataset.
   - **Inference**: Evaluates test images and stores the annotated outputs in the `./results` folder.

## Authors / License
Developed by the SpaceaLab team.
