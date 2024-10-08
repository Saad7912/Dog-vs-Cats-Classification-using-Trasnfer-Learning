# Dog vs. Cats Classification using Transfer Learning with MobileNetV2

This repository contains code and resources for a Dog vs. Cats Classification project utilizing Transfer Learning with MobileNetV2. The project aims to build a highly accurate model capable of distinguishing between images of dogs and cats.

## Repository Structure

- **train.py**: A Python script to train the MobileNetV2 model on the dog vs. cat dataset. It handles model training and saves the trained model for later use.
- **test.py**: A Python script for evaluating the model's performance on a test dataset. It provides accuracy and other performance metrics.
- **scripts/predict.py**: A Python script for making predictions on new images using the trained model. It takes an image as input and outputs whether it's a dog or a cat.

## Installation

### Clone the Repository

```bash
https://github.com/Saad7912/Dog-vs-Cats-Classification-using-Trasnfer-Learning.git
```

### Navigate to the Project Directory
```bash
cd Dog-vs-Cats-Classification-using-Transfer-Learning
```

### Note: Ensure you have the following packages installed
TensorFlow
TensorFlow Hub
Keras
NumPy
Matplotlib

### Usage
#### 1. Train the Model
```bash
python scripts/train_model.py
```
#### 2. Evaluate the Model
```bash
python scripts/evaluate_model.py
```
#### 3. Make Predictions
```bash
python scripts/predict.py --image_path path/to/image.jpg
```

