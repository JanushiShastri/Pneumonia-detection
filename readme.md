# Chest X-Ray Image Classification

This repository contains a deep learning-based application for classifying chest X-ray images into two categories: "Pneumonia" and "Normal". The model is built using Keras and can be easily deployed as a web application using Streamlit.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)

## Overview

The purpose of this project is to provide a simple yet effective tool for medical professionals or researchers to classify chest X-ray images. The model classifies images into two categories:

1. **Pneumonia**: The image is indicative of pneumonia.
2. **Normal**: The image does not show signs of pneumonia.

The application is built using Streamlit, which allows users to upload images and get instant predictions.

## Installation

### Prerequisites

Ensure you have Python 3.x installed. The following libraries are required:

- `streamlit`
- `tensorflow`
- `keras`
- `numpy`
- `PIL`

You can install the dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage

To run the Streamlit app locally, navigate to the project directory and execute:

```bash
streamlit run main.py
```

This will start a local web server. You can then open your browser and go to http://localhost:8501 to use the application.

## How to Use

- Upload a chest X-ray image.

- The model will automatically process the image and provide a prediction: "Pneumonia" or "Normal".

### Model

The model is a Keras-based deep learning model trained to classify chest X-ray images. It uses a convolutional neural network (CNN) architecture to achieve high accuracy on the classification task. The model was trained using Teachable Machine.

### Labels

The labels used in this project are:

0: Pneumonia

1: Normal

These are defined in the labels.txt file.

## Dataset
https://data.mendeley.com/datasets/rscbjbr9sj/2
