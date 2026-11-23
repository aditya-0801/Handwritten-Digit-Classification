# Handwritten Digit Classification using MNIST

## About the Project

I built this project to explore how Deep Learning can be used to recognize handwritten digits.

For this project, I used the MNIST dataset, which contains thousands of handwritten digit images from 0 to 9. I trained an Artificial Neural Network (ANN) to identify these digits and predict the correct number from an image.

The main goal was to understand the complete workflow of an image classification project, starting from loading and preprocessing data to training and evaluating a neural network.

## Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset

I used the MNIST dataset, which consists of:

- 60,000 training images
- 10,000 testing images
- Image size of 28 × 28 pixels
- 10 different digit classes (0–9)
- Grayscale images

The dataset was loaded directly using TensorFlow/Keras.

## What I Did in This Project

1. Loaded the MNIST dataset.
2. Explored and visualized handwritten digit samples.
3. Normalized image pixel values between 0 and 1.
4. Built an Artificial Neural Network using Keras.
5. Trained the model using the training dataset.
6. Evaluated its performance on unseen test images.
7. Generated predictions for handwritten digits.
8. Created accuracy and loss graphs.
9. Evaluated the predictions using a classification report and confusion matrix.
10. Saved the trained model for future use.

## Model Architecture

The model uses the following layers:

- Flatten Layer – Converts the 28 × 28 image into a one-dimensional array.
- Dense Layer – 128 neurons with ReLU activation.
- Dropout Layer – Helps reduce overfitting.
- Dense Layer – 64 neurons with ReLU activation.
- Output Layer – 10 neurons with Softmax activation.

## Results and Evaluation

I evaluated the model using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The notebook includes visualizations of training accuracy, validation accuracy, training loss, validation loss, and actual versus predicted digits.

## How to Run the Project

1. Clone this repository:

   `git clone https://github.com/YOUR_USERNAME/Handwritten-Digit-Classification.git`

2. Open the project folder.

3. Install the required libraries:

   `pip install tensorflow numpy matplotlib seaborn scikit-learn`

4. Open Jupyter Notebook:

   `jupyter notebook`

5. Open `Handwritten_Digit_Classification.ipynb` and run the cells.

## What I Learned

While working on this project, I gained practical experience with image preprocessing, neural network architecture, model training, prediction, and performance evaluation.

It also helped me understand how Deep Learning models can be applied to real-world image classification problems.

## Future Improvements

- Implement a Convolutional Neural Network (CNN).
- Compare ANN and CNN performance.
- Build a simple web application for handwritten digit prediction.

---

**This project is part of my learning journey in Artificial Intelligence and Machine Learning.**
