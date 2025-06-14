# Underwater-trash-detection-rcnn
A deep learning project using Region-based Convolutional Neural Networks (RCNN) to detect and classify underwater trash. This system helps monitor marine pollution by identifying debris like plastic, metal, and organic waste from underwater images.

Underwater Trash Detection using RCNN

This project implements a Region-based Convolutional Neural Network (RCNN) to detect and classify underwater trash in images and video frames. The model helps support marine conservation by automatically identifying common types of underwater debris such as plastic, metal, and organic waste.

## Project Structure

`rcnn_final.ipynb` — Main notebook containing the full training and inference pipeline
`outputs/` — Detection result images with bounding boxes and labels

## Model Overview

- **Architecture**: Faster RCNN with ResNet-50 FPN backbone
- **Framework**: PyTorch (torchvision)
- **Input**: Underwater RGB images
- **Output**: Bounding boxes and class labels for trash objects

## Dataset

A custom dataset of underwater images annotated with bounding boxes around different categories of trash:

- Classes: `plastic`, `metal`, `organic`, `other`
- Format: COCO-style annotations
- Tools used: makesense.ai


## 🔧 Setup

1. Clone the repo:
```bash
git clone https://github.com/Mndarish/Underwater-trash-detection-rcnn.git
cd Underwater-trash-detection-rcnn
pip install -r requirements.txt


