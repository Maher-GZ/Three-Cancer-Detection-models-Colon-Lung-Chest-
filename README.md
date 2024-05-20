# Three-Cancer-Detection-models-Colon-Lung-Chest-

This computer vision project contains deep learning models for detecting cancer in colon, chest, and lung tissues using convolutional neural networks (CNNs). The data for lung and colon cancers comes from histopathological images, while chest cancer detection is based on chest X-ray images.

## Contents

1. [Data](#data)
2. [Models](#models)
3. [Results](#results)
4. [License](#license)
5. [Acknowledgements](#acknowledgements)

## Data

The data used in this project can be found from the following sources:

- **Lung and Colon Cancer**: The lung and colon data is sourced from the Kaggle dataset [Lung and Colon Cancer Histopathological Images](https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images). It consists of:

    - **Lung**: A total of 750 images (250 benign lung tissue, 250 lung adenocarcinomas, and 250 lung squamous cell carcinomas).
    - **Colon**: A total of 500 images (250 benign colon tissue and 250 colon adenocarcinomas), augmented to 25,000 images using the Augmentor package.

- **Chest Cancer**: The chest data is sourced from the Kaggle dataset [Chest X-Ray Pneumonia](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia). It consists of:

    - **Chest**: A total of 5,863 X-ray images organized into train, test, and validation folders with subfolders for each category (Pneumonia/Normal).

## Models

The repository contains CNN models for each type of cancer detection:

- **Colon Cancer Detector**: Uses a CNN to classify histopathological images of colon tissue into benign or adenocarcinoma categories.
- **Lung Cancer Detector**: Uses a CNN to classify histopathological images of lung tissue into benign, adenocarcinoma, or squamous cell carcinoma categories.
- **Chest Cancer Detector**: Uses a CNN to classify chest X-ray images into pneumonia or normal categories.

## Results

The results of the trained models are reported in the respective model scripts. Metrics such as accuracy, precision, recall, and F1-score are calculated to evaluate model performance.

## 

Thank you to the creators of the datasets for making them available for use in this project.
