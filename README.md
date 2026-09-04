# Handwritten Digit Classification using ANN

## 📌 Project Overview

This project uses an **Artificial Neural Network (ANN)** to classify handwritten digit images from **0 to 9** using the MNIST dataset. The model is built using **TensorFlow and Keras** and learns patterns from 28×28 pixel images to predict the corresponding digit.

## 📊 Dataset

The **MNIST dataset** contains:

* **60,000** training images
* **10,000** test images
* Image size: **28 × 28 pixels**
* **10 classes:** digits 0–9

## 🧠 Model Architecture

The ANN consists of the following layers:

```text
Input Image (28 × 28)
        ↓
Flatten Layer
        ↓
Dense Layer (32 neurons, ReLU)
        ↓
Dense Layer (128 neurons, ReLU)
        ↓
Output Layer (10 neurons, Softmax)
```

### Model Configuration

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Cross-Entropy
* **Evaluation Metric:** Accuracy
* **Epochs:** 25
* **Validation Split:** 20%

## 🔄 Project Workflow

1. Import required libraries
2. Load the MNIST dataset
3. Explore the dataset
4. Visualize sample images
5. Normalize pixel values between 0 and 1
6. Build the ANN model
7. Compile the model
8. Train the model
9. Evaluate the model on test data
10. Analyze training and validation performance
11. Test individual handwritten digit predictions

## 📈 Results

The trained ANN achieved **97.35% accuracy** on the test dataset.

The project also includes training and validation **loss and accuracy curves** to observe model performance during training.

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 📁 Project Structure

```text
handwritten-digit-classification/
│
├── Handwritten_Digit_Classification_using_ANN.ipynb
└── README.md
```

## 🎯 Conclusion

This project demonstrates how an Artificial Neural Network can be used for handwritten digit classification. The model successfully learns from MNIST images and achieves high classification accuracy on unseen test data.
