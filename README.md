# -Transfer-Learning-for-Food-Image-Classification



# Overview
This Python script demonstrates the process of transfer learning using PyTorch for classifying food images into three categories: pizza, sushi, and steak. The script utilizes the EfficientNet_B0 model from torchvision and fine-tunes it on a custom dataset.

# Dependencies
Python 3.x
PyTorch 1.12+
torchvision 0.13+
torchinfo
mlxtend
tqdm
matplotlib
PIL

# Dataset
The script downloads a dataset containing pizza, sushi, and steak images from GitHub. The data is organized into training and testing sets.

# Transfer Learning
The script uses the EfficientNet_B0 model with pretrained weights from ImageNet.
The base layers of the model are frozen to serve as a feature extractor.
A new classifier layer is added to the model for the specific classification task.
The model is trained on the custom dataset using cross-entropy loss and the Adam optimizer.
# Evaluation
The model's performance is evaluated on the test dataset, and a confusion matrix is generated to visualize the results. Additionally, the script identifies and plots the top 5 most misclassified images.

# Prediction and Visualization
The script provides functions to make predictions on individual images and visualize the results. Example usage is demonstrated with a resized pizza image.

Feel free to explore and modify the script for your own image classification tasks.
