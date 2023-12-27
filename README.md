# Pneumonia-Detection
## Project Overview
The aim of this project is to analyze data from the [NIH Chest X-ray Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) and train a CNN to classify a given Chest X-Ray for the presence or absence of pneumonia.

## Dataset Background
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). The dataset contains two kinds of chest X-ray Images: NORMAL and PNEUMONIA, which are stored in two folders. In the PNEUMONIA folder, two types of specifc PNEUMONIA can be recognized by the fle name: BACTERIA and VIRUS.

## Requirements
- Tensorflow 2.x 
- Keras 
- Matplotlib 
- Numpy 
- Sklearn 
- OpenCV

You can install the requirements using the following command:
```
pip install -r requirements.txt
```

## Data Background
The dataset contains two classes, Normal and Pneumonia.
The dataset is divided into two sets, one for training and the other for testing.
The images are resized and normalised before being fed into the model.

## Results
The model achieved an accuracy of 96% on the test dataset.

## Todo
- Link frontend and backend