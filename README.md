# Valorant Object Detection

This repository contains the code for an object detection model trained to detect enemy heads in the game Valorant. The model is trained using the Ultralytics YOLOv8n model and a dataset exported from Roboflow.

## About the Dataset

The dataset includes 1570 images with annotations in YOLOv8 format. Each image has been pre-processed to auto-orient the pixel data and resized to 416x416. Augmentation has been applied to create 3 versions of each source image with a random Gaussian blur of between 0 and 0.5 pixels.

## Requirements

- Python 3.8 or later
- Ultralytics YOLO
- MSS
- PIL
- Numpy
- Interception Driver
- Winsound
- OpenCV

## Usage

To run the object detection model, execute the following command:

```bash
python main.py
```

## License

```plaintext
This project is licensed under the MIT License.
```
