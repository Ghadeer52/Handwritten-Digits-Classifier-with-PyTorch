### Developing a Handwritten Digits Classifier with PyTorch

## Project Overview

This project involves building a convolutional neural network (CNN) using PyTorch to classify handwritten digits from the MNIST dataset. The goal is to achieve high accuracy in identifying digits from 0 to 9, leveraging deep learning techniques.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Installation

To get started, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/Ghadeer52/Handwritten-Digits-Classifier-with-PyTorch.git
cd Handwritten-Digits-Classifier-with-PyTorch
pip install -r requirements.txt
```
## Dataset
The dataset used for this project is the MNIST dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits.

## Project Structure
- notebooks/: Jupyter notebooks containing the analysis and model training code.
- data/: Directory where the dataset is stored.
- models/: Saved models and training checkpoints.
- scripts/: Python scripts for data loading, model training, and evaluation.
- README.md: Project documentation.
  
## Usage
To train the model and make predictions, follow these steps:

Data Loading: Load the dataset for training and testing.

```bash
python scripts/load_data.py
Model Training: Train the CNN using the provided notebook.
```

```bash
jupyter notebook notebooks/train_model.ipynb
Evaluation: Evaluate the trained model on the test set.
```

```bash
python scripts/evaluate_model.py
```
## Results
The project achieves high accuracy in classifying handwritten digits. Detailed results and model performance metrics are available in the results/ directory.

# Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.
