# Drowsiness Detection System

## Overview
This project is aimed at developing a drowsiness detection system using computer vision techniques and deep learning. The system detects the state of eyes in real-time video streams and raises an alert if signs of drowsiness are detected.

## Features
- Real-time detection of closed eyes indicating drowsiness.
- Alarm triggering when drowsiness is detected.
- Adjustable sensitivity threshold for drowsiness detection.
- Utilizes Convolutional Neural Networks (CNN) for accurate eye state classification.
- Easy to use and integrate into existing systems.

## Requirements
- Python 3.x
- OpenCV
- Keras
- Pygame

## Usage
1. Run the `drowsiness_detection.py` script to start the drowsiness detection system.
2. Adjust the sensitivity threshold in the script if necessary to fine-tune the detection accuracy.
3. Ensure proper lighting conditions and camera setup for optimal performance.

## Model Training
- The CNN model used for eye state classification can be retrained or fine-tuned for better performance.
- Use the `model.py` script to train the model with your own dataset or modify the existing model architecture.


## Acknowledgements
- This project utilizes pre-trained Haar cascade classifiers for face and eye detection.
- The CNN model architecture is inspired by various research papers and tutorials in the field of computer vision.
