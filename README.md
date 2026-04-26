# 🎓 Fundamentals of Machine Learning

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/MonicAuditya/Fundamentals-of-Machine-Learning)
![GitHub stars](https://img.shields.io/github/stars/MonicAuditya/Fundamentals-of-Machine-Learning?style=social)
![GitHub forks](https://img.shields.io/github/forks/MonicAuditya/Fundamentals-of-Machine-Learning?style=social)
![GitHub issues](https://img.shields.io/github/issues/MonicAuditya/Fundamentals-of-Machine-Learning)
![GitHub license](https://img.shields.io/github/license/MonicAuditya/Fundamentals-of-Machine-Learning)

**A comprehensive collection of Machine Learning Lab Experiments & Haya AI Project**

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [🧪 Lab Experiments](#-lab-experiments)
- [🤖 Haya AI Project](#-haya-ai-project)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [📋 Requirements](#-requirements)
- [📚 Learning Outcomes](#-learning-outcomes)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🌟 Overview

This repository contains two major components:

1. **LabExperiments** - A complete set of hands-on machine learning experiments covering fundamental to advanced ML concepts
2. **Haya-Project** - An innovative AI-powered mobile application built with cutting-edge technology

Each lab experiment is designed to provide practical understanding of machine learning algorithms, from basic concepts to complex implementations.

---

## 🧪 Lab Experiments

### 📌 LAB 1a - Introduction to Machine Learning & Iris Classification
**Files:** `FOML lab 1a.ipynb`, `lab 1a.ipynb`, `iris.csv`

Learn the basics of ML with the classic Iris dataset. Covers:
- Data loading and exploration
- Feature visualization
- Basic classification algorithms
- Model evaluation metrics

### 📌 LAB 1b - Diabetes Prediction
**Files:** `lab 1b.ipynb`, `diabetes.csv`

Binary classification problem for diabetes prediction:
- Data preprocessing
- Handling imbalanced datasets
- Logistic Regression implementation
- Performance metrics (Accuracy, Precision, Recall, F1-Score)

### 📌 LAB 2 - Linear Regression
**Files:** `Linear_Regression.ipynb`, `Experience-Salary.csv`

Predict salary based on years of experience:
- Simple Linear Regression
- Cost function visualization
- Gradient Descent optimization
- R² Score and model evaluation

### 📌 LAB 3 - Logistic Regression
**Files:** `Logistic_Regression.ipynb`, `student_exam_data.csv`

Multi-class classification for student exam performance:
- Sigmoid function implementation
- Decision boundaries
- One-vs-Rest classification
- Confusion matrix analysis

### 📌 LAB 4 - Single Layer Perceptron
**Files:** `Single_layer_perceptron.ipynb`, `logical_gate.csv`

Neural network fundamentals:
- Perceptron learning algorithm
- Logic gate implementations (AND, OR, NOT)
- Activation functions
- Weight updates and convergence

### 📌 LAB 5 - Multi-Layer Perceptron
**Files:** `Multi_layer_perceptron.ipynb`, `XOR_Dataset.csv`

Deep learning basics:
- Hidden layer architecture
- Backpropagation algorithm
- XOR problem solution
- Loss function optimization

### 📌 LAB 6 - Face Recognition using SVM
**Files:** `Face_Recognition_using_SVM.ipynb`, `haarcascade_frontalface_default.xml`, `Data/`

Computer Vision application:
- Haar Cascade face detection
- Support Vector Machine classification
- Feature extraction
- Multi-class celebrity recognition (5 classes)
  - Ben Affleck
  - Elton John
  - Jerry Seinfeld
  - Madonna
  - Mindy Kaling

### 📌 LAB 7 - Decision Tree
**Files:** `Decision_Tree.ipynb`, `student-por.csv`

Student performance prediction:
- Tree-based algorithms
- Gini Impurity & Information Gain
- Feature importance analysis
- Pruning techniques

### 📌 LAB 8 - Boosting Algorithms
**Files:** `boosting.ipynb`, `breast-cancer.csv`

Ensemble learning methods:
- AdaBoost implementation
- Gradient Boosting
- XGBoost integration
- Breast cancer classification

### 📌 LAB 9a - K-Nearest Neighbors (KNN)
**Files:** `KNN.ipynb`, `penguins.csv`

Instance-based learning with Palmer Penguins dataset:
- K value selection
- Distance metrics (Euclidean, Manhattan)
- Cross-validation
- Feature scaling importance

### 📌 LAB 9b - K-Means Clustering
**Files:** `K-means.ipynb`, `penguins.csv`

Unsupervised learning:
- Clustering algorithms
- Elbow method for optimal K
- Cluster visualization
- Silhouette analysis

### 📌 LAB 10 - Principal Component Analysis (PCA)
**Files:** `PCA.ipynb`, `penguins.csv`

Dimensionality reduction:
- Eigenvalues and Eigenvectors
- Variance explanation
- Feature transformation
- Data visualization in 2D/3D

---

## 🤖 Haya AI Project

<div align="center">

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Kotlin](https://img.shields.io/badge/Language-Kotlin-purple)
![AI](https://img.shields.io/badge/AI-LLaMA-orange)
![Native](https://img.shields.io/badge/Backend-C%2FC%2B%2B-blue)

</div>

**Haya** is an advanced AI-powered mobile application that brings the power of Large Language Models (LLMs) to your Android device.

### ✨ Features

- 🧠 **On-Device AI** - Run LLM models locally on your device
- 🔒 **Privacy First** - All processing happens on-device, no data leaves your phone
- ⚡ **Optimized Performance** - Custom native backend for efficient inference
- 📱 **Modern UI** - Beautiful, intuitive Kotlin-based interface
- 🌐 **Multiple Models** - Support for various LLM model formats

### 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| **Mobile App** | Kotlin, Android SDK |
| **AI Backend** | C/C++, llama.cpp |
| **Neural Engine** | Custom RedHat1406 implementation |
| **Build System** | CMake, Gradle |
| **Architecture** | MVVM Pattern |

### 📂 Project Highlights

```
Haya-Project/
├── app/                  # Main Android application
│   ├── src/main/        # App source code (Kotlin)
│   └── build.gradle     # App dependencies
├── llama.cpp/           # LLaMA inference engine
│   ├── ggml/           # Tensor computation library
│   └── src/            # Core ML implementation
├── redhat1406/          # Custom neural network module
│   ├── src/main/cpp/   # Native C++ code
│   └── build.gradle    # Native build config
└── resources/           # App assets & metadata
```

---

## 📁 Project Structure

```
Fundamentals-of-Machine-Learning/
│
├── 📂 Haya-Project/
│   ├── 📂 app/                          # Android Application
│   │   ├── 📂 src/main/
│   │   │   ├── 📂 java/                # Kotlin source files
│   │   │   ├── 📂 res/                 # Android resources
│   │   │   └── AndroidManifest.xml
│   │   └── build.gradle
│   │
│   ├── 📂 llama.cpp/                    # LLaMA Inference Engine
│   │   ├── 📂 ggml/                    # Tensor Library
│   │   ├── 📂 src/                     # Core Implementation
│   │   ├── 📂 common/                  # Shared Utilities
│   │   └── 📂 vendor/                  # Dependencies
│   │
│   ├── 📂 redhat1406/                   # Custom Neural Module
│   │   ├── 📂 src/main/cpp/           # Native C++ Code
│   │   └── build.gradle
│   │
│   ├── 📂 metadata/                     # Play Store Metadata
│   │   └── 📂 en-US/
│   │       ├── 📂 images/
│   │       └── 📂 changelogs/
│   │
│   └── 📂 resources/                    # App Assets
│       ├── 📂 app_icon/
│       └── 📂 app_screenshots/
│
└── 📂 LabExp/                           # Laboratory Experiments
    │
    ├── 📂 LAB1a/                        # Introduction to ML
    │   ├── FOML lab 1a.ipynb
    │   ├── lab 1a.ipynb
    │   └── iris.csv
    │
    ├── 📂 LAB1b/                        # Diabetes Prediction
    │   ├── lab 1b.ipynb
    │   └── diabetes.csv
    │
    ├── 📂 LAB2/                         # Linear Regression
    │   ├── Linear_Regression.ipynb
    │   └── Experience-Salary.csv
    │
    ├── 📂 LAB3/                         # Logistic Regression
    │   ├── Logistic_Regression.ipynb
    │   └── student_exam_data.csv
    │
    ├── 📂 LAB4/                         # Single Layer Perceptron
    │   ├── Single_layer_perceptron.ipynb
    │   └── logical_gate.csv
    │
    ├── 📂 LAB5/                         # Multi-Layer Perceptron
    │   ├── Multi_layer_perceptron.ipynb
    │   └── XOR_Dataset.csv
    │
    ├── 📂 LAB6/                         # Face Recognition (SVM)
    │   ├── Face_Recognition_using_SVM.ipynb
    │   ├── haarcascade_frontalface_default.xml
    │   └── 📂 Data/
    │       ├── 📂 train/               # Training Images
    │       │   ├── 📂 ben_afflek/
    │       │   ├── 📂 elton_john/
    │       │   ├── 📂 jerry_seinfeld/
    │       │   ├── 📂 madonna/
    │       │   └── 📂 mindy_kaling/
    │       └── 📂 test/                # Test Images
    │
    ├── 📂 LAB7/                         # Decision Tree
    │   ├── Decision_Tree.ipynb
    │   └── student-por.csv
    │
    ├── 📂 LAB8/                         # Boosting Algorithms
    │   ├── boosting.ipynb
    │   └── breast-cancer.csv
    │
    ├── 📂 LAB9a/                        # K-Nearest Neighbors
    │   ├── KNN.ipynb
    │   └── penguins.csv
    │
    ├── 📂 LAB9b/                        # K-Means Clustering
    │   ├── K-means.ipynb
    │   └── penguins.csv
    │
    └── 📂 LAB10/                        # Principal Component Analysis
        ├── PCA.ipynb
        └── penguins.csv
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Android Studio (for Haya Project)
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/MonicAuditya/Fundamentals-of-Machine-Learning.git

# Navigate to the directory
cd Fundamentals-of-Machine-Learning

# Install Python dependencies
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# For Lab 6 (Face Recognition)
pip install opencv-python pillow

# For Lab 8 (Boosting)
pip install xgboost lightgbm
```

### Running Lab Experiments

```bash
# Start Jupyter Notebook
jupyter notebook

# Navigate to any Lab folder and open the .ipynb files
# Example: LabExp/LAB1a/lab 1a.ipynb
```

### Building Haya Project

```bash
# Open in Android Studio
# File -> Open -> Select Haya-Project folder
# Sync Gradle files
# Build -> Make Project
# Run on emulator or physical device
```

---

## 📋 Requirements

### Lab Experiments

```txt
numpy>=1.21.0
pandas>=1.3.0
scikit-learn>=0.24.0
matplotlib>=3.4.0
seaborn>=0.11.0
jupyter>=1.0.0
opencv-python>=4.5.0  # For LAB6
xgboost>=1.4.0        # For LAB8
```

### Haya Project

- Android Studio Arctic Fox or later
- Android SDK 21+
- NDK 23+
- CMake 3.10+

---

## 📚 Learning Outcomes

After completing these lab experiments, you will understand:

✅ **Supervised Learning** - Classification & Regression algorithms  
✅ **Unsupervised Learning** - Clustering & Dimensionality Reduction  
✅ **Neural Networks** - From Perceptron to Deep Learning  
✅ **Ensemble Methods** - Boosting & Bagging techniques  
✅ **Model Evaluation** - Metrics, Cross-validation, Hyperparameter tuning  
✅ **Real-world Applications** - Face Recognition, Medical Diagnosis, Performance Prediction  

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ by Monic Auditya**

[GitHub](https://github.com/MonicAuditya) • [LinkedIn](https://linkedin.com/in/monicauditya) • [Email](mailto:monicauditya@example.com)

⭐ **Star this repo if you find it helpful!**

</div>
