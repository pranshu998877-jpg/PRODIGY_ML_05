# Image Classification Model - Task 05 (Prodigy InfoTech Internship)

This repository contains the code and implementation for Task 05 of the Machine Learning Internship at Prodigy InfoTech. The project implements an image classification pipeline using a Random Forest Classifier and OpenCV.

## Project Overview
- **Task:** Image Classification (Task 05)
- **Model:** Random Forest Classifier (`scikit-learn`)
- **Image Processing:** OpenCV (`cv2`), NumPy
- **Environment:** Jupyter Notebook (`trackcode_05.ipynb`)

## Dataset
This project utilizes the [Food-101 Dataset](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) (or relevant image dataset categories used during experimentation). 
- **Dataset Link:** [Download Food-101 Dataset on Kaggle](https://www.kaggle.com/datasets/dansbecker/food-101)

## Features
- Automated directory scanning and dataset path detection.
- Grayscale conversion and image resizing (64x64 pixels) for efficient feature extraction.
- Train-test split (80-20 ratio) for robust model validation.
- Performance evaluation using Accuracy Score and Classification Report.

## Tech Stack
- Python 3.x
- scikit-learn
- OpenCV
- NumPy
- Jupyter Notebook

## How to Run
1. Clone the repository and ensure your dataset folder is placed in the root directory.
2. Open `trackcode_05.ipynb` in VS Code or Jupyter Notebook.
3. Run the cells sequentially to load images, train the Random Forest model, and view the classification accuracy.
