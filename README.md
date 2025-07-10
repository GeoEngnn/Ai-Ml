# Ai-Ml
Skin Cancer Detection Using CNN
A deep learning project that classifies skin lesion images as benign or malignant using a Convolutional Neural Network (CNN). Built as part of the AICTE – Edunet Foundation Internship (AI with Azure).

📁 Dataset
Name: Melanoma Skin Cancer Dataset

Source: [Kaggle or ISIC if applicable]

Classes: Benign, Malignant

Images resized to 224x224

🚀 Technologies Used
Python

TensorFlow & Keras

Google Colab

NumPy, Matplotlib, Seaborn

Scikit-learn

📊 Model Overview
CNN with 3 Conv2D layers, MaxPooling, Dense layers, Dropout

Binary classification (Sigmoid activation)

Optimizer: Adam

Loss Function: Binary Crossentropy

Epochs: 25

Accuracy: ~92% on validation data

📈 Results
Plots of training/validation accuracy and loss

Confusion Matrix and Classification Report

Sample predictions with image visualization

🔮 Future Scope
Add multi-class skin disease classification

Use transfer learning (e.g., ResNet, VGG16)

Deploy as a web/mobile app

Integrate explainable AI for interpretability

📂 How to Run
Open the notebook in Google Colab

Upload the dataset ZIP file

Train the model (or load skin_cancer_cnn.h5)

Run prediction on test images

