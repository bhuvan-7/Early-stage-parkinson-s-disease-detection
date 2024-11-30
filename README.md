
# Early-Stage Parkinson's Disease Detection

Welcome to the **Early-Stage Parkinson's Disease Detection** repository! This project uses machine learning to detect Parkinson's disease at an early stage through analysis of spiral and wavy drawings. The model is trained to classify the severity of the disease using images of handwritten shapes, providing a potentially valuable tool for early diagnosis.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Features](#features)
4. [Model Details](#model-details)
5. [Usage](#usage)


---

## Project Overview

Parkinson's disease is a neurodegenerative disorder that can impair motor skills. One early indicator of Parkinson's disease is the difficulty in drawing spiral and wavy shapes. In this project, we built a model that classifies whether the drawings represent a healthy or Parkinson's-affected individual. The model uses a deep learning approach with pre-trained VGG16 for feature extraction, followed by additional layers for classification.

---

## Installation

To use this project on your local machine, follow the steps below:

### Requirements

- Python 3.x
- TensorFlow 2.x
- Keras
- OpenCV
- Flask (for deployment)
- Git (for version control)

## Features
Deep Learning-based Model: Trained with VGG16 for feature extraction and additional dense layers for classification.
Data Preprocessing: Preprocessing includes resizing images, normalizing pixel values, and using data augmentation techniques.
Web Deployment: The model is deployed as a web application using Flask. Users can upload images to classify them.
Git LFS Support: Large .h5 model file is stored using Git LFS.

## Model Details
The model is built using VGG16 as a pre-trained base for feature extraction. It is fine-tuned with custom layers on top to classify images of spiral and wavy drawings into two categories: Healthy and Parkinson.

Input Size: 128x128x3
Output Classes: 2 (Healthy, Parkinson)
Training Dataset: Spiral and wavy drawings collected from healthy and Parkinson's-affected individuals.

## Usage

### To run the model and classify images, follow these steps:

1. Start the Flask app: python app.py

2. Go to the web interface: http://127.0.0.1:5000/

3. Upload a spiral/wavy drawing.

4. View the prediction result: "Healthy" or "Parkinson."







