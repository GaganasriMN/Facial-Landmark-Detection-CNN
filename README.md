# Facial Landmark Detection using CNN

## Overview

This repository contains code for facial landmark detection using Convolutional Neural Networks (CNN). The project involves predicting keypoint positions on face images, which can be used in various applications such as facial tracking, expression analysis, medical diagnosis, biometrics, and face recognition.

## Dataset

The dataset used for training can be found in the '[(https://www.kaggle.com/datasets/nagasai524/facial-keypoint-detection)]' file. It contains facial keypoint coordinates and image pixel values.

## Model Architecture

The CNN model architecture is defined in the `model.py` file. It consists of several convolutional layers followed by max-pooling and fully connected layers.

## Training

The model is trained using the training dataset, and the training process is logged in the `training_history.log` file. The best model is saved in `checkpoint.hdf5`.

```bash
