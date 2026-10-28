# Handwritten Character Recognition using CNN

## Project Overview
This project identifies handwritten digits from 0 to 9 using a Convolutional Neural Network (CNN) and the MNIST dataset.

## Objective
To develop a deep learning model that recognizes handwritten digits from image data.

## Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- MNIST Dataset
- Google Colab

## Methodology
1. Load the MNIST dataset.
2. Normalize image pixel values between 0 and 1.
3. Reshape images for CNN input.
4. Build a CNN model.
5. Train the model for 5 epochs.
6. Evaluate the model on test images.
7. Predict handwritten digits.

## Model Performance
- Training accuracy: 98.35%
- Validation accuracy: 98.72%
- Test accuracy: 98.76%
- Test loss: 0.0381

## Sample Prediction
The model correctly predicted the digit 7, matching the actual label 7.

## How to Run
1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells in order.
3. The MNIST dataset downloads automatically.
4. Train and evaluate the CNN model.

## Project Files
- `CodeAlpha_HandwrittenCharacterRecognition.ipynb` — source code and experiment.
- `CodeAlpha_HandwrittenCharacterRecognition.keras` — trained model.

## Conclusion
The CNN model achieved 98.76% test accuracy on the MNIST test dataset.

**Internship:** CodeAlpha Machine Learning Internship  
**Task:** Handwritten Character Recognition
