# Sign-Language-recognize-using-cnn
This project implements a Convolutional Neural Network (CNN) to recognize American Sign Language (ASL) alphabet gestures from images.

this model Trained on the Kaggle ASL Alphabet dataset, the model classifies 29 classes (A-Z, del, nothing, space). It uses TensorFlow/Keras for model building, data augmentation to prevent overfitting, and callbacks for efficient training. The prediction pipeline processes input images to identify ASL signs in real-time. Ideal for learning image classification and deep learning concepts.

# How It Works

Data: Downloads and preprocesses the ASL Alphabet dataset from Kaggle.

Model: A CNN with convolutional, pooling, and dense layers, enhanced with L2 regularization and dropout.

Training: Uses data augmentation (rotation, zoom, etc.) and callbacks (EarlyStopping, ModelCheckpoint) to train robustly.

save: and to save the model for further use i use here  " model.save("sign_language_model_final.h5") "

Prediction: Resizes and normalizes input images to predict the  ASL sign and use opencv for capture image.
