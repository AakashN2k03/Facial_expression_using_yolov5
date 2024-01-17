# Facial Expression Recognition with YOLOv5

This project implements facial expression recognition using YOLOv5, a state-of-the-art object detection framework. The model is trained to detect faces and predict the corresponding facial expressions.

## Getting Started

### Prerequisites

Make sure you have the following prerequisites installed:

- Python 
- PyTorch
- OpenCV
- YOLOv5 (follow the YOLOv5 installation instructions [here](https://github.com/ultralytics/yolov5))

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/AakashN2k03/Facial_expression_using_yolov5.git

2. follow the steps performed on the notebook
3. Training-> use - !cd yolov5 && python train.py --img 320 --batch 16 --epochs 500 --data dataset.yml --weights yolov5s.pt --workers 2

   ### Reference
   
   Documentation -> https://github.com/ultralytics/yolov5

   For labelling images -> https://github.com/tzutalin/labelImg
   
   Reference repository -> https://github.com/nicknochnack/YOLO-Drowsiness-Detection
