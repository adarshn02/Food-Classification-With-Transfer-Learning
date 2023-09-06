# Food Classification with Transfer Learning

Welcome to the Food Classification with Transfer Learning project! This beginner-friendly project focuses on computer vision-based food classification using TensorFlow. We explore the power of transfer learning by comparing the performance of two popular architectures, ResNet and EfficientNet, on a 10-class food classification task.

## Table of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Running Transfer Learning Experiments](#running-transfer-learning-experiments)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Transfer learning is a powerful technique in deep learning, allowing us to leverage pre-trained models to solve new tasks more efficiently. In this project, we apply transfer learning to classify food items into 10 different classes using TensorFlow, ResNet, and EfficientNet.

## Project Overview

- **Classification Task**: Food classification into 10 classes.
- **Transfer Learning Models**: We compare the performance of ResNet and EfficientNet.
- **TensorFlow Hub**: Utilizing TensorFlow Hub for pre-trained models.
- **TensorBoard**: Comparing and visualizing results using TensorBoard.
- **Data**: Using a portion of the dataset (not the complete dataset) for experimentation.
- **Keras Functional API**: Implementing transfer learning with the Keras Functional API.

## Key Features

- Comparison of ResNet and EfficientNet for transfer learning.
- Running experiments with different amounts of training data.
- Model evaluation using accuracy metrics.
- Visualizing and comparing results with TensorBoard.

## Project Structure

The project consists of three Jupyter notebooks:

1. `04_transfer_learning_in_tensorfow_1_feature_extraction.ipynb`: Feature extraction transfer learning experiments.
2. `05_transfer_learning_fine_tuning.ipynb`: Fine-tuning transfer learning experiments.
3. `06_Transfer_Learning_Part_3_scaling_up.ipynb`: Scaling up transfer learning experiments.

## Getting Started

To get started with this project, follow these steps:

1. Clone or download this repository to your local machine.

2. Set up your Python environment with TensorFlow and other dependencies.

3. Open the Jupyter notebooks in your preferred environment.

4. Run the notebooks to explore and replicate the transfer learning experiments.

## Running Transfer Learning Experiments

We conducted a series of transfer learning experiments, including:

1. 'model_1' - Feature extraction transfer learning with 1% of training data with data augmentation.
2. 'model_2' - Feature extraction transfer learning with 10% of training data with data augmentation.
3. 'model_3' - Fine-tuning transfer learning on 10% of training data with data augmentation.
4. 'model_4' - Fine-tuning with 100% of training data with data augmentation.

## Results

Our preliminary results (using a portion of the dataset) showed the following accuracy rates:

- ResNet Accuracy: 74.92%
- EfficientNet Accuracy: 86.64%

These results demonstrate the potential of transfer learning for food classification.

## Contributing

Contributions to this project are welcome! If you have improvements, corrections, or additional experiments to add, please open an issue or submit a pull request.
