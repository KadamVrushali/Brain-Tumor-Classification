# Brain-Tumor-Classification
This repository contains a deep learning project for brain tumor classification using Convolutional Neural Networks (CNN) and Histogram of Oriented Gradients (HOG) features. The models are trained on medical imaging datasets to accurately classify glioma, meningioma, no-tumor, and pituitary tumors.

### Overview of Contents
🧠  Data Visualization: Analyzing class imbalance and tracking model performance through graphs like loss vs. epoch and accuracy vs. epoch.

🧠  Model Development: Crafting effective architectures for CNN and HOG feature extraction.

🧠 Training & Assessment: Fitting the models and evaluating performance using metrics such as accuracy and F1-score.

### Results
##### CNN Model
Accuracy: 87.95%
Loss: 0.2956
Classification Report:
              precision    recall  f1-score   support
      glioma       0.91      0.77      0.84       300
  meningioma       0.74      0.76      0.75       306
     notumor       0.91      0.99      0.95       405
   pituitary       0.95      0.97      0.96       300

##### HOG Model
Accuracy: 84.74%
Loss: 0.3899
Classification Report:
              precision    recall  f1-score   support
      glioma       0.87      0.83      0.85       300
  meningioma       0.78      0.54      0.64       306
     notumor       0.84      1.00      0.91       405
   pituitary       0.89      0.97      0.93       300
