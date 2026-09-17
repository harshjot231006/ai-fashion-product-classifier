# Fashion Product Image Classification

A Deep Learning project that classifies fashion product images into different product categories using **TensorFlow/Keras** and the **Fashion MNIST dataset**.

## 📌 Project Overview

In e-commerce, thousands of product images may need to be categorized before products are added to an online store. Manual categorization can be repetitive and time-consuming.

This project demonstrates how a simple **Artificial Neural Network (ANN)** can analyze fashion product images and predict their product category.

### Business Problem

An e-commerce company receives a large number of product images and needs to categorize them efficiently.

**Input:** Product image
**Output:** Predicted product category

The model can assist employees by automatically suggesting the appropriate category for each product image.

## 🎯 Learning Objectives

This project demonstrates how to:

* Use images as input for a Deep Learning model
* Load and explore the Fashion MNIST dataset
* Prepare image data for model training
* Build a simple Artificial Neural Network
* Understand input, hidden, and output layers
* Train a neural network using labelled images
* Evaluate model performance using test accuracy
* Predict product categories from unseen images
* Connect an AI model with an e-commerce business use case

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
* **Google Colab**
* **Fashion MNIST Dataset**

## 📊 Product Categories

The model classifies images into 10 categories:

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## 🧠 Model Architecture

The project uses a simple Artificial Neural Network:

```text
Input Image
     ↓
Flatten Layer
     ↓
Dense Hidden Layer (64 neurons)
     ↓
ReLU Activation
     ↓
Output Layer (10 categories)
     ↓
Softmax
     ↓
Predicted Product Category
```

### Model Configuration

* **Input:** 28 × 28 pixel image
* **Hidden Layer:** Dense layer with 64 neurons
* **Hidden Activation:** ReLU
* **Output Layer:** 10 neurons
* **Output Activation:** Softmax
* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Training:** 3 epochs
* **Validation Split:** 10%

## 🔄 Project Workflow

```text
Load Fashion MNIST Dataset
          ↓
Explore Product Images
          ↓
Normalize Pixel Values
          ↓
Build Neural Network
          ↓
Compile Model
          ↓
Train Model
          ↓
Evaluate Test Accuracy
          ↓
Predict Unseen Images
          ↓
Compare Predicted vs Actual Category
```

## 💼 Business Application

The model can be used as an **AI-assisted product categorization tool** for an e-commerce platform.

### Traditional Process

```text
Product Image
     ↓
Employee Manually Identifies Category
     ↓
Product Added to Website
```

### AI-Assisted Process

```text
Product Image
     ↓
Deep Learning Model
     ↓
Predicted Category
     ↓
Employee Review if Required
     ↓
Product Added to Website
```

### Potential Business Benefits

* Faster product listing
* Reduced repetitive manual work
* More consistent product categorization
* Improved product-search experience
* Ability to process larger volumes of product images

## 📈 Model Evaluation

The model is evaluated using **test accuracy** on images that were not used during training.

Accuracy represents the proportion of test images that were classified correctly.

However, accuracy alone may not be sufficient for real-world deployment. Businesses should also consider:

* Cost of incorrect classification
* Customer experience
* Quality of training data
* Human review requirements
* Potential business risks

## ⚠️ Limitations

This project uses a relatively simple neural network and the Fashion MNIST dataset for demonstration purposes.

The model may produce incorrect predictions. In a real e-commerce environment, additional validation, better datasets, stronger models, and appropriate human oversight may be required before deployment.

## 📁 Project Structure

```text
fashion-product-image-classification/
│
├── Deep_Learning_Fashion_Classification_Name.ipynb
├── README.md
└── screenshots/
    └── prediction-result.png
```

## 🚀 How to Run

1. Open the notebook in **Google Colab**.
2. Run the cells sequentially.
3. The Fashion MNIST dataset will be downloaded automatically.
4. Train the neural network for 3 epochs.
5. Evaluate the model using the test dataset.
6. Test different image numbers to view predictions.
7. Compare the predicted category with the actual category.

## 🎓 Academic Context

This project demonstrates the application of **Deep Learning and Artificial Neural Networks** to a practical business problem.

It connects technical concepts such as neural networks, activation functions, training, testing, and prediction with an **e-commerce product categorization use case**.

## 👤 Project Type

**Domain:** Artificial Intelligence / Machine Learning / E-commerce
**Technique:** Deep Learning – Artificial Neural Network
**Dataset:** Fashion MNIST
**Framework:** TensorFlow/Keras
**Environment:** Google Colab
