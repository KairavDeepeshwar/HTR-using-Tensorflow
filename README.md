# Handwritten Character Recognition

This project aims to recognize handwritten characters using deep learning techniques. The model is trained on a dataset containing handwritten characters and validated on a separate dataset. The model architecture includes convolutional layers followed by fully connected layers for classification.

## Dataset

The dataset used for training and validation consists of handwritten characters. It is divided into two parts: training and validation. The training dataset contains images of handwritten characters used for training the model, while the validation dataset is used to evaluate the model's performance.

## Model Architecture

The model architecture consists of convolutional layers for feature extraction followed by fully connected layers for classification. Dropout layers are incorporated to reduce overfitting. The model is compiled using the Adam optimizer and categorical cross-entropy loss function.

## Training

The model is trained using the training dataset with data augmentation techniques to improve generalization. Data augmentation includes random rotations, shifts, shears, zooms, and flips. Early stopping is employed based on validation loss to prevent overfitting.

## Evaluation

The trained model is evaluated on the validation dataset to assess its performance. Metrics such as accuracy and loss are monitored during training and validation. Training and validation curves are plotted to visualize the model's performance.

## Results

The trained model achieves an accuracy of 91.24% on the validation dataset.
