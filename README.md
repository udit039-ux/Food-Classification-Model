# Food Classification Model

This project implements a food image classification model using PyTorch to classify images into three categories: pizza, steak, and sushi.

## Overview

The notebook `Food_Classification_Model.ipynb` contains the complete workflow from data preparation to model evaluation, including:

- Importing necessary libraries and setting up device-agnostic code
- Downloading and preparing the food image dataset
- Transforming data into PyTorch tensors and DataLoaders
- Creating and training a convolutional neural network (CNN) model
- Evaluating the model performance
- Making predictions on custom images

## Features

- **Data Handling**: Custom dataset creation for image classification
- **Model Architecture**: CNN-based model with transfer learning capabilities
- **Training**: Efficient training loop with loss tracking and accuracy metrics
- **Visualization**: Plotting training curves and confusion matrices
- **Inference**: Real-time prediction on new images

## Requirements

- Python 3.7+
- PyTorch >= 1.10.0
- torchvision
- matplotlib
- numpy
- requests
- Jupyter Notebook or VS Code with Python extension

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/udit039-ux/Food-Classification-Model.git
   cd Food-Classification-Model
   ```

2. Install dependencies:
   ```bash
   pip install torch torchvision matplotlib numpy requests
   ```

## Usage

1. Open `Food_Classification_Model.ipynb` in Jupyter Notebook or VS Code
2. Run the cells sequentially to:
   - Set up the environment
   - Download and extract the dataset
   - Train the model
   - Evaluate performance
   - Make predictions

## Dataset

The project uses a custom dataset of food images categorized into:
- Pizza
- Steak
- Sushi

The dataset is automatically downloaded and extracted during notebook execution.

## Model Architecture

The model uses a pre-trained EfficientNet backbone with custom classification head for the three food categories.

## Results

After training, the model achieves high accuracy on the test set. Training progress and evaluation metrics are visualized in the notebook.

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is for educational purposes.