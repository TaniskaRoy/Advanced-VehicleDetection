# Advanced-Vehicle-Detection

This repository contains the code and data for the Advanced Vehicle Detection (AVD) Hackathon. The goal of this project is to develop an automatic vehicle detection system that can accurately identify and classify vehicles in images captured under various weather conditions. This system is crucial for Intelligent Transportation Systems (ITS) and smart city applications, including self-driving cars and driver assistance systems. The dataset is available here: [github.com/Sourajit-Maity/juvdv2-vdvwc](https://github.com/Sourajit-Maity/juvdv2-vdvwc).
<br>
Arrange the data by creating 2 subfolders in the `data` folder, named `images` and `labels`. Keep the images in the `images` folder, and the annotations in the `labels` folder.

## Repository Structure

- `best_output.txt`: Contains the text of the best output.
- `config.yaml`: Configuration file for setting up the dataset paths and other parameters.
- `data/`: Folder containing the dataset arranged in YOLO format.
- `main.py`: The main script to run the vehicle detection system.
- `runs/`: Directory for storing model outputs and logs.
- `supplementary.py`: Additional script used for supporting tasks.

## Getting Started

### Prerequisites

Ensure you have the following packages installed:

```bash
pip install torch torchvision timm ultralytics






Developed an object detection system using **YOLOv10** to detect vehicles in various weather conditions.

 **AVD-Dataset**: Utilized the AVD-Dataset, consisting of 3,200 annotated vehicle images in YOLO format across 15 classes, with 2,600 images for training and 200 for validation.
  
**Model Implementation**:
  - **YOLOv10x**: Implemented the YOLOv10x model, achieving an **mAP@50** score of **0.598**, an **F1 score** of **0.60**, and a **Precision** of **0.70** for both training and validation datasets.
  - **YOLOv10n & Earlier Versions**: Conducted experiments with **YOLOv10n** and previous versions, resulting in an **mAP@50** score of **0.49**.
  - **YOLOv10m**: Implemented the **YOLOv10m** model with medium-weight backbones, achieving an **mAP@50** score of **0.53**.
  - **MobileNetV2**: Also tested **MobileNetV2**, which achieved an **mAP@50** score of **0.51**, an **F1 score** of **0.55**, and **Precision** of **0.67**.
  
**Recognition**: Secured **first runner-up** position in the **Jadavpur University Hackathon 2024** for this object detection system.

