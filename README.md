# CNN for Image Classification on CIFAR-10

This repository contains an implementation of a Convolutional Neural Network (CNN) for image classification using the CIFAR-10 dataset. The project was developed as part of an academic assignment and includes both the research report and executable code.

---

## 📂 Project Structure
- `Report.docx` – Detailed report of the project.
- `cnn_cifar10.ipynb` – Jupyter Notebook with implementation.
- `requirements.txt` – Python dependencies.

---

## 📊 Dataset
- **Dataset**: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)  
- 60,000 images (32x32, RGB) across 10 categories.  
- Preprocessing included normalization, reshaping, and train-validation split (80:20).

---

## 🏗️ Model Architecture
- Convolutional layers for feature extraction  
- MaxPooling layers for downsampling  
- Fully Connected layers for classification  
- ReLU activation in hidden layers  
- Softmax activation in output layer  

**Optimizer:** Adam  
**Loss Function:** Categorical Cross-Entropy  
**Metric:** Accuracy  

---

## 📈 Training & Evaluation
- Trained for 20 epochs, batch size = 64  
- Applied **data augmentation** for better generalization  
- Evaluated using accuracy, precision, recall, F1 score  

**Test Accuracy:** **62.57%**

---

## 📊 Results
- Confusion Matrix to visualize class-level performance  
- Training & Validation accuracy/loss plots  
- Sample predictions on test data  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/jawadahmad-05/cnn-cifar10-classification.git
   cd cnn-cifar10-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook cnn_cifar10.ipynb
   ```

---
