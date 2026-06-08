# Image Classification using Transfer Learning with ResNet18

## Overview

This project implements an Image Classification model using Transfer Learning with a pretrained ResNet18 architecture on the CIFAR-10 dataset. The model is trained using PyTorch and evaluated using standard classification metrics.

## Dataset

The CIFAR-10 dataset contains 60,000 color images belonging to 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Technologies Used

* Python
* PyTorch
* Torchvision
* Jupyter Notebook
* Matplotlib
* Scikit-Learn

## Features

* Transfer Learning using pretrained ResNet18
* Data Augmentation
* Model Training and Evaluation
* Accuracy, Precision, Recall, and F1-Score Calculation
* Training Visualization Graphs
* Saved Model for Inference

## Project Structure

### Project Structure

1. T2_ImageClassification.ipynb
2. saved_model.pth
3. T2_Report.pdf
4. README.md
5. screenshots/

## Model Performance

| Metric    | Score |
| --------- | ----- |
| Accuracy  | 80%   |
| Precision | 81%   |
| Recall    | 80%   |
| F1-Score  | 80%   |

## How to Run

### Install Required Libraries

### pip install torch torchvision matplotlib scikit-learn

### Run the Notebook

Open:

### T2_ImageClassification.ipynb

and execute all cells sequentially.

## Load Saved Model

### model.load_state_dict(torch.load("saved_model.pth")) model.eval()

## Results

The model successfully classified CIFAR-10 images using transfer learning and achieved approximately 80% test accuracy.

## Internship

Project completed as part of the InternSpark Internship Program.
