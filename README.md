Wild Cat Species Classification Using Deep Learning
Overview
This project implements deep learning models for image classification, specifically for identifying different wild cat species. Using a dataset containing images of species like cheetahs, ocelots, snow leopards, caracals, lions, pumas, and tigers, the models are trained to classify images accurately. The project includes data preprocessing, model training, evaluation, and optimization using various machine learning techniques.

Key Features
Data Processing: Images are loaded, resized, normalized, and converted into structured datasets.
Model Training: Three types of models are implemented:
Fully Connected Neural Network (FCNN) – Simple feedforward model.
Convolutional Neural Network (CNN) – Deep learning-based feature extraction.
Optimized CNN (Grid Search & Augmentation) – Improved model using hyperparameter tuning.
Evaluation & Optimization:
Performance measured using accuracy and mean squared error.
K-Fold Cross-Validation ensures robust model evaluation.
Hyperparameter tuning improves accuracy using Grid Search.
Visualization: Accuracy and loss trends are plotted for better insights.
Model Saving & Deployment: Trained models are saved in pickle (.h5) format for reuse.
