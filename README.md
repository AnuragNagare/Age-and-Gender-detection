# Age and Gender Detection with OpenCV

This repository contains code for age and gender detection using OpenCV's deep learning-based face detection model and pre-trained age and gender classification models.

## Dependencies

Make sure you have the following dependencies installed:

- OpenCV
- argparse

## Usage

To run the age and gender detection on an image or video, use the following command:

python age_gender_detection.py --image path/to/image.jpg


If no image path is provided, the code will attempt to use the webcam.

## Models

The code uses the following pre-trained models:

- Face detection: opencv_face_detector.pbtxt, opencv_face_detector_uint8.pb
- Age classification: age_deploy.prototxt, age_net.caffemodel
- Gender classification: gender_deploy.prototxt, gender_net.caffemodel

## Results

The code detects faces in the input image or video and overlays bounding boxes on the detected faces. It then predicts the age and gender for each face and displays the results on the image or video.



