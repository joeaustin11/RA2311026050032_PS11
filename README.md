# Rice Grain Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify rice grains into five varieties based on their images. The model is trained and evaluated using TensorFlow and Keras in Google Colab.

## Rice Varieties
The model classifies the following five rice varieties:
- Arborio
- Basmati
- Ipsala
- Jasmine
- Karacadag

## Dataset
- **Total images:** 5,000
- **Classes:** 5
- **Images per class:** 1,000
- **Training images:** 4,000
- **Validation images:** 1,000
- **Image size:** 224 × 224 pixels

A balanced subset was created from the original dataset to ensure an equal number of images for each class.

## Model Architecture
The CNN model was built using TensorFlow and Keras with the following layers:
- Image rescaling
- Convolutional layers with ReLU activation
- Max pooling layers
- Flatten layer
- Fully connected dense layer
- Dropout layer
- Softmax output layer for five-class classification

The model was compiled using the Adam optimizer and categorical cross-entropy loss, with early stopping to help prevent overfitting.

## Results
The trained model achieved the following performance on the validation dataset:

- **Accuracy:** 98.20%
- **Macro F1-score:** 98.20%
- **Weighted F1-score:** 98.20%

The classification report and confusion matrix were generated to evaluate the model's performance across all five rice varieties.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Model File
The trained model is saved as `rice_classifier.keras` in Google Drive. The model file is not uploaded to this repository because of GitHub's file-size limit for regular browser uploads.

## Google Colab Notebook
[Open the Google Colab Notebook](https://colab.research.google.com/drive/1FqYQolganmVms-NN2Y6BdUbH97atA83Q?usp=sharing)

## Project Outputs
This repository contains the following output files:
- `accuracy_graph.png` — Model accuracy visualization
- `loss_graph.png` — Model loss visualization
- `confusion_matrix.png` — Confusion matrix for classification results
- `joe austin cbl.ipynb` — Project notebook

## Conclusion
This project demonstrates how CNNs can be used for image-based rice grain classification. The model achieved 98.20% validation accuracy on a balanced dataset of five rice varieties.

## Author
Joe Austin Martin T.
