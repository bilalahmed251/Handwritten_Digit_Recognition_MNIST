# Handwritten_Digit_Recognition_MNIST

## 📌 Project Overview
The goal of this project is to build a model that can accurately classify images of handwritten digits. This is a fundamental step in understanding how machines "see" and process visual information.

## 🧠 Approach & Methodology
To achieve high accuracy in digit classification, I followed these steps:

## Data Normalization:
Scaled pixel values from [0, 255] to [0, 1] to help the model converge faster.
## Flattening: 
Converted 28x28 images into a 1D array for traditional machine learning algorithms.
## Algorithm Testing: 
Experimented with various classifiers to find the most robust solution for image data.

## 🛠️ Technical Workflow

## Exploratory Data Analysis (EDA): 
Visualized sample digits using matplotlib to understand the data distribution.
## Preprocessing: 
Reshaped and normalized the training and testing sets.
## Model Training: 
Trained the classifier on 60,000 images and validated it on 10,000 unseen images.
## Evaluation: 
Generated a Confusion Matrix to see which digits (like 4 and 9) the model was confusing most often.

## Tech Stack:

## Language:
Python
## Libraries:
Numpy, Matplotlib, Scikit-Learn
## Dataset:
MNIST (Modified National Institute of Standards and Technology)

## 📂 Repository Structure:
├── Digit_Recognition.ipynb  
├── digit_model.pkl          
└── README.md                
