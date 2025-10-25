# Gender and Age Prediction

## Project Overview
This project implements a deep learning-based system capable of predicting both gender and age from facial images.  
Built using TensorFlow and Keras, the model utilizes a multi-output Convolutional Neural Network (CNN) that performs dual predictions efficiently.

---

## Key Features
- Dual Prediction System: Simultaneously predicts gender (male/female) and age (numerical value).  
- Dataset: Uses the UTKFace dataset, containing thousands of facial images with labeled age, gender, and ethnicity.  
- Model Architecture:
  - Multiple Convolutional Layers (32, 64, 128, 256 filters)
  - MaxPooling Layers for feature extraction
  - Dropout Layers for regularization
  - Dual Output Heads for gender classification and age regression  
- Training Configuration:
  - Loss Functions:  
    - Gender → Binary Cross-Entropy  
    - Age → Mean Absolute Error (MAE)
  - Optimizer: Adam  
  - Batch Size: 32  
  - Epochs: 30  
  - Validation Split: 20%  
- Image Processing: Converts images to grayscale and resizes them to 128×128 pixels.  
- Visualization: Displays accuracy, loss, and MAE trends using Matplotlib and Seaborn.

---

## Tech Stack
- Frameworks: TensorFlow, Keras  
- Languages & Libraries: Python, NumPy, Pandas, Matplotlib, Seaborn, PIL, tqdm  

---

## Model Performance
- Gender Classification: Binary output → Male / Female  
- Age Prediction: Continuous regression output → Predicted numerical age  
- Evaluation Metrics: Accuracy, MAE, and visual plots of model performance  

---

## Sample Usage 
This model takes a grayscale facial image as input and output
1. Gender Prediction(male/female)
2. Age Prediction(numeric value)
