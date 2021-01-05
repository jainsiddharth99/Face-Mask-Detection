[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
# Face Mask Detection
It is a real time face mask detection.

## Requirements
- Keras
- Tensorflow
- OpenCV 

## Model
I have used resnet50 as it has better accuracy but i have also tested it with mobilenetv2.

## Dataset
As we are detecting mask on a face we have to train the model which can differentiate between face with mask and face witout mask.

## Setup
1. Install required libraries
2. Download dataset from kaggle
3. Train the model using train_mask_detector.py
4. Run detect_mask_video.py to detect face mask using your webcam



