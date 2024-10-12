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

The project is organized as follows:
├── data/ # Contains the dataset (training, validation, testing) │ ├── train/ # Training data │ ├── val/ # Validation data │ └── test/ # Testing data ├── models/ # Saved trained models │ ├── vgg16/ # VGG16 trained model files │ ├── mobilenetv3/ # MobileNetV3 trained model files │ └── inceptionv3/ # InceptionV3 trained model files ├── notebooks/ # Jupyter notebooks for experimentation │ ├── vgg16_notebook.ipynb # VGG16 model training and evaluation notebook │ ├── mobilenetv3_notebook.ipynb # MobileNetV3 model notebook │ └── inceptionv3_notebook.ipynb # InceptionV3 model notebook ├── src/ # Source code for data processing, model training, and evaluation │ ├── preprocess.py # Code for data preprocessing │ ├── train_vgg16.py # Code for training VGG16 model │ ├── train_mobilenetv3.py # Code for training MobileNetV3 model │ └── train_inceptionv3.py # Code for training InceptionV3 model ├── README.md # Project documentation ├── requirements.txt # Python dependencies └── LICENSE # License for the project



## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/mahmoud3wwd/brain-tumor-detection.git
   cd brain-tumor-detection

   
