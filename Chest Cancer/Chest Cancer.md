# Chest Cancer Detection using CNN

This repository contains a convolutional neural network (CNN) model for detecting pneumonia in chest X-ray images. The data consists of pediatric chest X-rays and includes images of pneumonia and normal chest X-rays.

## Contents

1. [Data](#data)
2. [Model](#model)

## Data

The chest X-ray data is sourced from the Kaggle dataset [Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). It consists of:

- **Chest X-rays**: A total of 5,863 images organized into train, test, and validation folders, with subfolders for each category (Pneumonia/Normal). The images are in JPEG format.

The data was obtained from Guangzhou Women and Children’s Medical Center, Guangzhou, China, and consists of anterior-posterior (AP) view images of pediatric patients aged one to five years old. All imaging was performed as part of routine clinical care.

## Model

The repository includes a CNN model for detecting pneumonia from chest X-ray images. The model is designed to classify images into two categories: pneumonia and normal. It is trained on the provided dataset and can be fine-tuned for improved performance.

