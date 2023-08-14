# Pneumonia Classification using X-ray Images with Keras

This repository contains code and resources for building a pneumonia classification model using X-ray images. The model is implemented using Keras and TensorFlow, and it's trained to differentiate between normal and pneumonia X-ray images.

## Dataset

The dataset used for this project is the [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) dataset from Kaggle. It includes X-ray images of both normal and pneumonia cases.

## Project Structure

- `x_ray.ipynb/` folder can be used to save trained model checkpoints.
- `requirements.txt` lists the required packages for the project.

## Usage

1. Organize your dataset in the following structure:
data/
  ├── train/
  │ ├── NORMAL/
  │ └── PNEUMONIA/
  ├── val/
  │ ├── NORMAL/
  │ └── PNEUMONIA/
  └── test/
  ├── NORMAL/
  └── PNEUMONIA/
2. Open and run the Jupyter notebooks in the `notebooks/` folder to preprocess the data, build the model, train, and evaluate it.
3. Alternatively, you can train and evaluate the model using the `main.py` script:


## Results

After training, the model's performance can be evaluated on the test set using metrics such as accuracy, precision, recall, and F1-score.

## Acknowledgments

This project is based on the Chest X-Ray Images (Pneumonia) dataset from Kaggle. Thanks to the dataset contributors and the Keras and TensorFlow communities for their tools and resources.
