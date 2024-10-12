# Brain-Tumor-Detection-Using-Transfer-Learning-in-tf

# Brain Tumor Detection Using Transfer Learning Models

This project implements a deep learning-based brain tumor detection system using three different pre-trained models: VGG16, MobileNetV3, and InceptionV3. The goal is to classify brain MRI images into two categories: **Tumor** and **Healthy**.

## Dataset

The dataset used for this project is from Kaggle: [Brain MRI Images for Brain Tumor Detection](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection). It contains MRI images categorized into two classes:
- **Tumor**: Images of patients with brain tumors.
- **Healthy**: Images of healthy brains.

### Dataset Structure:
- **Training Set**: Images used for training the models.
- **Validation Set**: Images used to validate model performance during training.
- **Test Set**: Images used for final evaluation of model accuracy.

## Models

Three pre-trained models are fine-tuned for this binary classification task:
1. **VGG16**
2. **MobileNetV3**
3. **InceptionV3**

These models have been chosen for their successful track record in image classification tasks and transfer learning capabilities. Transfer learning allows us to leverage pre-trained weights on large datasets, improving performance even with limited training data.

### Model Details:
- **VGG16**: A convolutional neural network that is 16 layers deep. It is known for its simplicity and efficiency for classification tasks.
- **MobileNetV3**: A mobile-friendly architecture that balances accuracy and efficiency with fewer parameters, optimized for embedded devices.
- **InceptionV3**: A deeper and wider network known for reducing computational cost by using "Inception" modules.

## Project Structure

