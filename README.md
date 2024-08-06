# Parking Spot Detection with Machine Learning

![Parking Spot Detection](https://github.com/cnguyen770/CompVisionParking/blob/master/visual.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

This project utilizes computer vision and machine learning to detect parking spots in real-time. The goal is to provide a robust solution for monitoring parking spaces using image classification techniques.

## Features

- Detects parking spots in real-time using a trained image classification model.
- High accuracy in varied lighting conditions and different parking lot layouts.
- Easily adaptable to different environments and camera setups.

## Installation

### Prerequisites

- Python 3.x
- Required Python libraries: `numpy`, `opencv-python`, `scikit-learn`, `skimage`
- Git

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/cnguyen770/CompVisionParking.git
    cd CompVisionParking
    ```


## Usage

### Training the Model

To train the image classification model:

```bash
python src/model/ImgClass.py
```

Running the Real-Time Detection
To start the real-time parking spot detection:

```bash
python src/main.py
