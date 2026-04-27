Handwritten Digit Classification (Perceptron vs ANN vs CNN)

Project Overview

This project compares three different machine learning models on the **MNIST handwritten digit dataset**:

* 🔹 Perceptron (Linear Model)
* 🔹 Artificial Neural Network (ANN)
* 🔹 Convolutional Neural Network (CNN)

The goal is to understand how model complexity affects performance in image classification tasks.

---

## Objectives

* Understand differences between linear and deep learning models
* Compare performance on image data
* Learn why CNNs outperform traditional neural networks
* Visualize predictions from different models

---

## Dataset

* **MNIST Dataset**
* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 (grayscale)
* Classes: Digits (0–9)

---

## Tech Stack

* Python 🐍
* NumPy & Pandas
* Matplotlib & Seaborn
* Scikit-learn
* TensorFlow / Keras

---

## Workflow

### 1️ Data Preprocessing

* Load dataset from CSV files
* Normalize pixel values (0–255 → 0–1)
* Reshape data:

  * ANN/Perceptron → (28×28)
  * CNN → (28×28×1)
* Apply one-hot encoding to labels

---

### 2️ Models Used

#### 🔹 Perceptron

* Single dense layer
* Linear classification
* Fast but limited performance

---

#### 🔹 Artificial Neural Network (ANN)

* Fully connected layers:

  * Dense (128, ReLU)
  * Dense (64, ReLU)
  * Output (Softmax)
* Learns non-linear patterns

---

#### 🔹 Convolutional Neural Network (CNN)

* Conv2D + MaxPooling layers
* Feature extraction from images
* Dropout for regularization
* Best performing model

---

## Results

| Model      | Accuracy (Approx) |
| ---------- | ----------------- |
| Perceptron | ~85–90%           |
| ANN        | ~95–97%           |
| CNN        | ~98–99%           |

---

## Visualization

The project includes a function to display:

* Input image
* True label
* Predictions from all models side-by-side

This helps in understanding model behavior.

---


---

## 📌 Key Learnings

* Linear models fail to capture image patterns
* ANN improves accuracy but ignores spatial structure
* CNN excels due to feature extraction capability
* Data preprocessing is critical for performance

---

## 🔮 Future Improvements

* Add data augmentation
* Use advanced CNN architectures
* Hyperparameter tuning
* Deploy model using Flask or FastAPI
* Convert to real-time digit recognition app

---

Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Harsh Raj**

---

⭐ If you found this project useful, consider giving it a star!
