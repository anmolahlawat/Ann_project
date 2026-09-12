# 🧠 Artificial Neural Network — Classification Project

A practical **Artificial Neural Network (ANN)** project built with **TensorFlow/Keras** to perform binary classification using a complete machine-learning-to-deep-learning workflow.

The project covers data preprocessing, feature transformation, ANN architecture design, model training, evaluation, and saving the trained model for future deployment.

---

## 🚀 Project Overview

This project demonstrates how an Artificial Neural Network can be used to learn patterns from structured/tabular data and make classification predictions.

### 🔄 Workflow

```text
Raw Dataset
     ↓
Data Preprocessing
     ↓
Train / Validation / Test Split
     ↓
Feature Transformation
     ↓
ANN Architecture
     ↓
Model Training
     ↓
Validation & Evaluation
     ↓
Model Saving
     ↓
🚀 Ready for Deployment
```

---

## 🧠 What I Built

The project includes:

* Data preprocessing pipeline
* Numerical and categorical feature handling
* Feature scaling
* Training / validation / test workflow
* Artificial Neural Network using Keras
* ReLU activation in hidden layers
* Sigmoid activation for binary classification
* Model compilation and optimization
* Training with validation data
* Model evaluation
* Prediction workflow
* Saved preprocessing pipeline
* Saved trained ANN model

---

## 🏗️ ANN Architecture

The neural network follows a standard feed-forward architecture:

```text
Input Features
      │
      ▼
┌─────────────────┐
│   Dense Layer   │
│      ReLU       │
└─────────────────┘
      │
      ▼
┌─────────────────┐
│   Dense Layer   │
│      ReLU       │
└─────────────────┘
      │
      ▼
┌─────────────────┐
│   Output Layer  │
│     Sigmoid     │
└─────────────────┘
      │
      ▼
 Binary Prediction
```

### Why these activations?

**ReLU**

Used in the hidden layers because it is computationally efficient and works well for learning nonlinear patterns.

**Sigmoid**

Used in the output layer because this project performs **binary classification**, producing a probability between `0` and `1`.

---

## 🛠️ Tech Stack

| Technology          | Purpose                      |
| ------------------- | ---------------------------- |
| 🐍 Python           | Programming language         |
| 🧠 TensorFlow       | Deep learning framework      |
| ⚡ Keras             | Neural network API           |
| 📊 Pandas           | Data manipulation            |
| 🔢 NumPy            | Numerical operations         |
| 📈 Scikit-learn     | Preprocessing & evaluation   |
| 📓 Jupyter Notebook | Development environment      |
| 💾 Joblib           | Saving preprocessing objects |
| 🗃️ Git/GitHub      | Version control              |

---

## 📁 Project Structure

```text
Ann_project/
│
├── 📓 ann_project.ipynb
├── 🧠 ann_model.keras
├── ⚙️ preprocessor.pkl
├── 📖 README.md
├── 🚫 .gitignore
└── 🐍 venv/              # Local environment (ignored)
```

### File Description

**`ann_project.ipynb`**

Contains the complete project workflow including preprocessing, ANN creation, training, evaluation, and predictions.

**`ann_model.keras`**

The trained TensorFlow/Keras ANN model saved in Keras format.

**`preprocessor.pkl`**

The fitted preprocessing pipeline used to transform input features before they are passed to the neural network.

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/anmolahlawat/Ann_project.git
cd Ann_project
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate it on macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install tensorflow pandas numpy scikit-learn jupyter joblib
```

Launch Jupyter:

```bash
jupyter notebook
```

Then open:

```text
ann_project.ipynb
```

---

## 🧪 Model Development Process

### 1️⃣ Data Preprocessing

The dataset is prepared before being passed to the neural network.

The preprocessing workflow handles:

* Numerical features
* Categorical features
* Feature scaling
* Categorical encoding
* Consistent transformations between training and inference

A reusable preprocessing pipeline is saved as:

```text
preprocessor.pkl
```

---

### 2️⃣ Neural Network Construction

The ANN is constructed using the Keras `Sequential` API.

The model contains:

* Input layer
* Hidden dense layers
* ReLU activation functions
* Binary classification output layer
* Sigmoid activation

---

### 3️⃣ Model Compilation

The network is compiled with an optimizer and binary classification loss function.

The training process monitors classification performance using accuracy and validation performance.

---

### 4️⃣ Model Training

The model learns patterns from the training data over multiple epochs while validation data is used to monitor generalization.

Conceptually:

```text
Training Data
      ↓
Forward Propagation
      ↓
Prediction
      ↓
Loss Calculation
      ↓
Backpropagation
      ↓
Weight Updates
      ↓
Repeat
```

---

### 5️⃣ Evaluation

The trained model is evaluated on unseen data to determine how well it generalizes beyond the training set.

Evaluation focuses on classification performance rather than simply memorizing the training examples.

---

## 💾 Model Persistence

The trained neural network is saved using the Keras model format:

```text
ann_model.keras
```

The preprocessing pipeline is saved separately:

```text
preprocessor.pkl
```

Keeping the preprocessing pipeline together with the model is important because **new data must undergo the same transformations used during training**.

---

## 🎯 Key Learning Outcomes

Through this project, I practiced:

* Understanding ANN architecture
* Designing dense neural networks
* Choosing activation functions
* Understanding forward propagation
* Understanding backpropagation
* Working with loss functions
* Model optimization
* Training neural networks with Keras
* Validation during training
* Evaluating deep learning models
* Saving and reusing trained models
* Building a preprocessing pipeline for inference
* Preparing a deep learning model for deployment

---

## 🔮 Future Improvements

Planned improvements include:

* [ ] Hyperparameter tuning
* [ ] Experiment with different ANN architectures
* [ ] Early stopping
* [ ] Learning-rate optimization
* [ ] Improved evaluation metrics
* [ ] Build a prediction API
* [ ] Deploy the trained model
* [ ] Create a user-friendly web interface
* [ ] Add Docker support

---

## 🚀 Deployment Roadmap

The project is structured with deployment in mind.

```text
ANN Model
   ↓
Saved Model (.keras)
   +
Preprocessor (.pkl)
   ↓
Prediction API
   ↓
Web Application
   ↓
☁️ Cloud Deployment
```

This allows the trained model to be separated from the development notebook and eventually used as a real-world prediction service.

---

## 📌 Project Status

**Status:** 🟢 Completed — Core ANN implementation

Deployment and production serving are planned as the next stage.

---

## 👨‍💻 Author

**Anmol Ahlawat**

B.Tech — Artificial Intelligence & Machine Learning

GitHub: **[@anmolahlawat](https://github.com/anmolahlawat)**

---

## ⭐ If You Found This Useful

If this project helped you understand Artificial Neural Networks, feel free to ⭐ the repository!

---

### 📚 Topics

`Python` `Deep Learning` `Artificial Neural Network` `ANN` `TensorFlow` `Keras` `Machine Learning` `Classification` `Scikit-Learn` `Neural Networks` `AI`
