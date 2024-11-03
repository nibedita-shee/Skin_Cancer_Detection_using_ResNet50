Skin_Cancer_Detection_using_ResNet50

This project aims to create a skin cancer detection model utilizing Convolutional Neural Networks (CNN). By harnessing the capabilities of TensorFlow and Keras, a skin cancer detection system was developed based on the ResNet-50 architecture. The model successfully achieved a commendable accuracy of 90.3% in differentiating skin lesions as either benign or malignant.

Description

Skin cancer is a widespread and potentially life-threatening condition. Timely detection is critical for improving patient outcomes. This project seeks to fulfill the demand for an automated skin cancer detection solution using advanced deep learning techniques.

Key features of this project include:

Application of the ResNet-50 model: The ResNet-50 architecture, recognized as a powerful and efficient CNN model, was employed for classifying skin cancer lesions in images.
Implementation with TensorFlow and Keras: The skin cancer classifier was developed using the TensorFlow and Keras frameworks, which provide a robust and efficient platform for deep learning applications.
High Accuracy: The resulting model achieved an impressive accuracy of 90.3% in classifying skin lesions, highlighting its utility in aiding dermatologists and healthcare professionals in skin cancer diagnosis.

Dataset
The skin cancer detector was trained on an extensive dataset of skin lesion images, which included multiple classes such as benign and malignant lesions. This dataset featured a diverse array of skin cancer types, ensuring that the model could generalize well across different cases.

Workflow
The project’s workflow comprised the following stages:

Data Preprocessing:

Loading and preparing the skin lesion images for analysis.
Dividing the dataset into training and testing subsets.
Implementing data augmentation techniques to enhance the model’s robustness.

Model Training:

Building the ResNet-50 model using TensorFlow and Keras.
Compiling the model with suitable loss functions and optimization algorithms.
Training the model on the prepared dataset.

Model Evaluation:

Assessing the trained model's performance using the testing set.
Computing essential metrics such as accuracy, precision, recall, and F1 score.

Skin Cancer Detection:

Applying the trained model to classify skin lesions in new, unseen images.
Producing predictions along with associated probabilities that indicate the likelihood of malignancy.

Results

The skin cancer classification model attained a notable accuracy of 90.3% on the validation set and 89.09% on the test set, successfully identifying malignant skin lesions in images. This accuracy level underscores the capability of deep learning models to assist dermatologists and healthcare practitioners in the diagnosis of skin cancer.


