# Classification Neural Network

This project demonstrates a simple binary classification task using a neural network implemented with PyTorch. It uses the `make_circles` dataset from scikit-learn, which is a classic example of a non-linear classification problem where a standard linear model would struggle.

## Overview

The notebook walks through the full workflow for training a small neural network:

- Generate a synthetic classification dataset
- Explore the data with pandas
- Visualize the class distribution with matplotlib
- Convert the data into PyTorch tensors
- Split the data into training and testing sets
- Build and train a two-layer neural network
- Evaluate performance using a binary classification loss function

## Project Structure

- `02_PyTorch_neural_network_classification.ipynb` — main notebook containing the full implementation and experiments

## Technologies Used

- Python
- PyTorch
- scikit-learn
- pandas
- matplotlib

## Model Architecture

The project uses a compact feedforward neural network with:

- Input layer: 2 features
- Hidden layer: 5 neurons
- Output layer: 1 neuron for binary classification

The model is trained using:

- `nn.BCEWithLogitsLoss()` for binary cross-entropy
- `torch.optim.SGD` as the optimizer
- `train_test_split` for data splitting

## Setup

1. Clone the repository
2. Create a virtual environment
3. Install the required Python libraries:

```bash
pip install torch pandas matplotlib scikit-learn jupyter
```

## Run the Project

Open the notebook in Jupyter or Google Colab and run the cells in order:

```bash
jupyter notebook
```

Then open:

```text
02_PyTorch_neural_network_classification.ipynb
```

## Example Workflow

The notebook includes the following steps:

1. Create the circles dataset
2. Inspect the samples and labels
3. Plot the training data
4. Convert arrays into PyTorch tensors
5. Define a neural network model
6. Train the model with SGD
7. Generate predictions and evaluate binary classification accuracy

## Expected Result

This project is intended to show how a small neural network can learn a non-linear decision boundary for a binary classification problem. It is a beginner-friendly example for understanding how PyTorch models are built, trained, and used in practice.

## Notes

This repository is notebook-based and focuses on educational demonstration rather than a production-ready application. It is best suited for learning the fundamentals of neural networks, datasets, and model training in PyTorch.
