Gender and Age Prediction
Description
This project implements a deep learning model that can simultaneously predict both the gender and age of a person from their facial image. It uses a multi-output Convolutional Neural Network (CNN) architecture built with TensorFlow and Keras.

Key Features
Dual prediction system (gender and age)
Uses UTKFace dataset
Implements a CNN with multiple convolutional layers
Real-time prediction capabilities
Grayscale image processing (128x128 pixels)
Visualization of training metrics and results
Technical Details
Framework: TensorFlow/Keras
Model Architecture:
Multiple Convolutional layers (32, 64, 128, 256 filters)
MaxPooling layers
Dropout layers for regularization
Dual output heads for gender and age prediction
Training:
Binary cross-entropy loss for gender
Mean Absolute Error (MAE) for age
Adam optimizer
Batch size of 32
30 epochs with 20% validation split
Libraries Used
TensorFlow/Keras
NumPy
Pandas
Matplotlib
Seaborn
PIL (Python Imaging Library)
tqdm
Model Performance
The model provides:
Gender classification (Binary: Male/Female)
Age regression (Continuous value prediction)
Visual performance metrics for both predictions

Sample Usage
The model takes a grayscale facial image as input and outputs:
Gender prediction (Male/Female)
Age prediction (numerical value)
