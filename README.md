# Deep Learning Based Dog Breed Classification

## Introduction

In the realm of computer vision, accurately identifying dog breeds from images represents a compelling application of deep learning technologies. This project harnesses the power of convolutional neural networks (CNNs) to develop a model that classifies images of dogs into their respective breeds. Leveraging a pre-trained MobileNetV2 model as a foundation, it is fine-tuned and augmented to specialize in dog breed classification.

The workflow encompasses several key phases:

- **Data Preparation:** Organizing a dataset of dog images into training, validation, and test sets;
- **Exploratory Data Analysis (EDA):** Inspecting the dataset for distribution and balance among classes;
- **Data Augmentation:** Implementing image augmentation techniques to enhance model generalization;
- **Model Building:** Utilizing MobileNetV2 as a base model, extending it with custom layers for breed classification;
- **Model Training and Fine-tuning:** Initial training with frozen base layers followed by fine-tuning select layers for optimization;
- **Evaluation:** Assessing the model's performance on unseen test data to gauge its accuracy and generalization capability.

### Objectives

- To create a highly accurate and efficient model capable of classifying dog breeds from images;
- To explore the effectiveness of transfer learning and fine-tuning in enhancing the performance of deep learning models in specific domains.

## Technologies Used

- Python 3.11.4;
- TensorFlow and Keras for model building and training;
- NumPy for numerical computations;
- Pandas for data manipulation;
- Matplotlib and PIL for image processing and visualization;
- Adam Optimizer for model optimization.

The project demonstrates the power of deep learning in image classification tasks and provides a foundation for further exploration into more complex classification challenges.

## Information about the data used in this project
The datasets used in this project was obtained from the public datasets section on Kaggle at the link https://www.kaggle.com/datasets/gpiosenka/70-dog-breedsimage-data-set.
