# Project Title: Mask R-CNN with ResNet-101 FPN for Thermal Imaging

## Overview

This project trains a **Mask R-CNN model** using the **ResNet-101 FPN (Feature Pyramid Network)** backbone for object detection and instance segmentation on a dataset of thermal images. The goal is to accurately detect and segment objects in thermal images, which are useful for various applications such as building inspections and anomaly detection.

The project is implemented using **Detectron2**, a powerful library for object detection and segmentation developed by Facebook AI Research (FAIR).

## Dataset

The dataset consists of **thermal images of building roofs**, where the objective is to detect and segment areas that exhibit thermal bridging. The dataset is in COCO format, containing `.npy` and `.json` files for annotations and image data.

[Dataset link] (https://zenodo.org/records/7022736)

### Dataset Structure
- **Images**: Thermal images taken from above, using a thermal camera.
- **Annotations**: Provided in COCO format, containing bounding boxes, segmentation masks, and labels for the thermal anomalies.

## Requirements

To run this project, you will need the following dependencies:

- Python 3.x
- Detectron2
- PyTorch
- OpenCV
- Matplotlib
- Numpy
- Jupyter Notebook (optional, for running and modifying the notebook)
