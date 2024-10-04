# Brain-Tumor-Classification
This repository hosts a deep learning project focused on brain tumor classification using Convolutional Neural Networks (CNN) and Histogram of Oriented Gradients (HOG) features. The models are trained on medical imaging datasets to accurately classify glioma, meningioma, no-tumor, and pituitary tumors.

## 🛠 Installation
To run this project, ensure you have Python and the following libraries installed:

tensorflow - keras
numpy
matplotlib
You can install the required packages using pip

## 🧠 Overview of Contents
Data Visualization: Analyzing class imbalance and tracking model performance through graphs like loss vs. epoch and accuracy vs. epoch.

Model Development: Crafting effective architectures for CNN and HOG feature extraction.

Training & Assessment: Fitting the models and evaluating performance using metrics such as accuracy and F1-score.

## 📈 Model Performance
After training the models, we achieved the following performance metrics:



#### CNN Model
Accuracy: 87.95%
Loss: 0.2956

```plaintext
              precision    recall  f1-score   support
      glioma       0.91      0.77      0.84       300
  meningioma       0.74      0.76      0.75       306
     notumor       0.91      0.99      0.95       405
   pituitary       0.95      0.97      0.96       300

```

#### HOG Model
Accuracy: 84.74%
Loss: 0.3899

```plaintext
              precision    recall  f1-score   support
      glioma       0.87      0.83      0.85       300
  meningioma       0.78      0.54      0.64       306
     notumor       0.84      1.00      0.91       405
   pituitary       0.89      0.97      0.93       300

```

## 📊 About HOG
Histogram of Oriented Gradients (HOG) is a feature descriptor that captures the gradient orientation and magnitude in localized regions of an image, making it effective for object detection tasks. HOG features are robust against changes in illumination and can be combined with traditional classifiers.

## 🧠 Why CNN is Better than HOG
While HOG provides valuable features for image classification, Convolutional Neural Networks (CNN) typically outperform HOG due to their ability to learn hierarchical representations directly from the raw pixel data. CNNs automatically detect patterns, edges, and shapes at multiple levels, leading to better feature extraction and improved classification accuracy. This capability makes CNNs particularly effective for complex tasks such as medical image analysis, where the intricacies of the data can significantly impact performance.
