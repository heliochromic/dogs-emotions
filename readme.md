# Dog Emotions

## Project Description
This project aims to analyze dog emotions using a neural network.

## Model Evaluation Metrics
The effectiveness of the model is assessed using the following metrics:
- **F1-score** - this metrics is used in cause of inbalanced classes in dataset with dogs emotions
- **Confusion Matrix** - this for better understanding of overall metrics of model

## Neural Network Architecture
The model is based on ResNet18, a deep convolutional neural network known for its efficiency in image classification tasks. This model was used because of the requirement to use a neural network written from scratch at this stage of this work (in this task I'm not allowed to use transfer learning). ResNet18 is small enough to provide one of the best performance and computational trade-offs.

## Running the Project

### Installing Dependencies
Before running the project, install all necessary dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Running the Code
Start Jupyter Notebook with:

```bash
jupyter notebook
```

Create a folder with `.zip` files for 4 classes, then open `datasets_preprocess.ipynb`, change `PATH` to folder with `.zip` files and execute all cells to preprocess the data

## Authors
This project was created as part of the **Deep Learning for Computer Vision** course at **Kyiv-Mohyla Academy** by **Bohdan Prokhorov**, a third-year student.
