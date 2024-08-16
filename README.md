# Dish Classification Using Pretrained Models on UEHVD-R Dataset

## Project Overview

This project focuses on classifying various dishes using the UEHVD-R dataset. The classification is performed using several pretrained models, including Xception, VGG19, and EfficientNet.

### Key Features

- **Pretrained Models**: Utilizes Xception, VGG19, and EfficientNet, which are fine-tuned on the UEHVD-R dataset to enhance classification accuracy.
- **Comprehensive Preprocessing**: Includes steps such as data augmentation and normalization to prepare the dataset for model training.
- **User Interface**: A simple UI is provided for users to interact with the model, allowing them to classify images of dishes easily.

## Project Workflow

1. **Data Preprocessing**
   - Augmentation and normalization of images from the UEHVD-R dataset.
   - Preparation of data for input into pretrained models.

2. **Model Training**
   - Fine-tuning of Xception, VGG19, and EfficientNet models on the processed dataset.
   - Evaluation of model performance based on accuracy and other relevant metrics.

3. **User Interface**
   - A user-friendly interface is provided to allow users to upload images and classify dishes using the trained models.

## Usage Instructions

- The entire workflow, including preprocessing, model training, and UI development, is implemented in the provided Jupyter notebook (`Dish_classification.ipynb`).
- Users can run the notebook to preprocess the data, train the models, and interact with the UI.

## Notes

- Please refer to the `Dish_classification.ipynb` file for detailed code and instructions.
- Ensure that all dependencies are installed as mentioned in the notebook before running the project.
