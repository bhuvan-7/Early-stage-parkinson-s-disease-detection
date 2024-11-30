# Early-stage-parkinson-s-disease-detection
# Early-Stage Parkinson's Disease Detection

Welcome to the **Early-Stage Parkinson's Disease Detection** repository! This project uses machine learning to detect Parkinson's disease at an early stage through analysis of spiral and wavy drawings. The model is trained to classify the severity of the disease using images of handwritten shapes, providing a potentially valuable tool for early diagnosis.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Features](#features)
4. [Model Details](#model-details)
5. [Usage](#usage)
6. [Folder Structure](#folder-structure)
7. [Contributing](#contributing)
8. [License](#license)

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

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Early-stage-parkinsons-disease-detection.git
