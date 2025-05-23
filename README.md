# Exposure Classification with CNN

This project uses a Convolutional Neural Network (CNN) to classify images based on their exposure into four categories:

-  **Overexposed**
-  **Underexposed**
-  **Poor Contrast**
-  **Normal**

It was developed using TensorFlow/Keras in Google Colab with a custom dataset.

## 🧠 Model Overview

The CNN model includes:

- Multiple Conv2D + MaxPooling layers
- Dropout and L2 Regularization to reduce overfitting
- Softmax output for multi-class classification
- Early stopping based on validation loss

## How to Run

You can run this project entirely in Google Colab. Follow the steps below:
- Upload the datset to google drive
- Mount the drive
- Insatll requirements
        -tensorflow>=2.8.0 ()
        -numpy
        -matplotlib
        -(pip install tensorflow numpy matplotlib)
- Download the file exposure_classifier_model.h5 which contains the trained model
  Download Link - https://drive.google.com/file/d/1u3KI3IXuZbWOoLLtme-HNRBSixSizvd0/view?usp=drive_link
- Load the model from drive and using model.predict Predict the output.
( Demo- image_classifier_modelcheck.ipynb for a complete walkthrough of prediction.)

**Building the Model from Scratch**

To train the model from scratch, refer to the notebook `image.ipynb`.  
Run each cell step-by-step, and be sure to **replace the dataset path** with the correct path to your own image folder on Google Drive.


## 📂 Dataset Structure

The dataset follow this folder structure:
dataset/
├── train_directory/
│ ├── normal/
│ ├── overexposed/
│ ├── underexposed/
│ └── poor contrast/
├── test_directory/
├── normal/
├── overexposed/
├── underexposed/
└── poor contrast/

Link to Download the Dataset - https://drive.google.com/drive/folders/1H0h-KLfbY9eRuS0ZjHYP645sNElxbU55?usp=drive_link

## 🚀 Project Workflow

 ![Project Workflow](flowchart.png)




