# Blood Group Prediction Using Fingerprint

## Project Overview

This project presents a **non-invasive approach** to blood group prediction using **fingerprint image processing** and **machine learning**. By leveraging **Convolutional Neural Networks (CNNs)**, the system classifies fingerprint patterns into **eight common blood groups**: A+, A-, B+, B-, AB+, AB-, O+, and O-. It aims to provide a **quick, accessible, and cost-effective** alternative to traditional blood testing methods.

---


## Objectives

* Rapid blood group identification with minimal processing time.
* Improved accessibility in remote or resource-limited areas.
* Compatibility with portable and point-of-care diagnostic devices.
* Reduced contamination risk through non-invasive methods.
* Integration of biometric analysis with medical diagnostics using machine learning.

---

## Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Flask
* SQLAlchemy
* SQLite

### Machine Learning

* TensorFlow / Keras
* Google Colab

---

## Model Performance

| Model                             | Testing Accuracy | Validation Accuracy |
| --------------------------------- | ---------------- | ------------------- |
| **VGG16**                         | 88.72%           | 89.50%              |
| **AlexNet**                       | 12.47%           | 12.49%              |
| **ResNet50**                      | 61.19%           | 62.70%              |
| **Hybrid (EfficientNetB0 + SVM)** | 22.29%           | 22.81%              |

---

## Dataset

**Source:** [https://www.kaggle.com/datasets/rajumavinmar/finger-print-based-blood-group-dataset](https://www.kaggle.com/datasets/rajumavinmar/finger-print-based-blood-group-dataset)

The dataset consists of fingerprint images labeled with corresponding blood groups. It is used for training, validation, and testing of the deep learning models.

---

## Application Screens

* Authentication and login interface
* Fingerprint upload module
* Blood group prediction result page

---

## Future Improvements

* Expansion of the dataset to improve generalization.
* Evaluation of advanced deep learning architectures for higher accuracy.
* Deployment of the model in a production or cloud environment.

---

## Contributors
1. Sonali Yadav
2. Swastika Tomar
3. Sneha
4. Swati Priyambda

---

Contributions are welcome. Feel free to fork the repository, open issues, or submit pull requests. If you find this project useful, consider starring the repository.
