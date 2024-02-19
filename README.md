# Dog Breed Identification Project

## Overview
This project aims to identify the breed of dogs from images using deep learning techniques, specifically transfer learning. The dataset consists of images of dogs belonging to 120 different breeds, with over 10,000 images in the training set and 10,000 images in the test set (unlabeled data). The images have been preprocessed into tensors for efficient processing.

## Dataset
- **Training Set**: Contains over 10,000 labeled images of dogs belonging to 120 different breeds.
- **Test Set**: Contains over 10,000 unlabeled images for evaluation.
- The data we will be using is from Kaggle's dog breed identification competion https://www.kaggle.com/c/dog-breed-identification

## Data Analysis
- Analyzed the dataset to understand the distribution of images among different dog breeds.
- Identified breeds with a large number of images and those with fewer images for potential data augmentation or balancing strategies.

## Preprocessing
- Preprocessed images by converting them into tensors.
- Developed a preprocessing function to:
  - Read image filepaths and convert them into TensorFlow variables.
  - Normalize the image data to scale color channel values from 0-255 to 0-1.
  - Resize images to a standardized shape of (224, 224).

## Model Training
- Utilized a Sequential Model to train the deep learning model on the preprocessed dataset.
- Employed transfer learning techniques to leverage pre-trained models for feature extraction and fine-tuning.
- Evaluated the performance of the model using the training dataset to assess its accuracy and effectiveness in breed identification.

## Contributors
- Sameer Batra (https://github.com/sameerbatra1/)
