# 🧠 ANN vs CNN Performance Benchmark for Image Classification

## 🚀 Overview
This project compares **Artificial Neural Networks (ANNs)** and **Convolutional Neural Networks (CNNs)** on **MNIST, Fashion MNIST, and CIFAR-10** datasets. The goal is to analyze their performance using **different activation functions, padding strategies, and hyperparameter tuning**.

## 📂 Project Structure
```
.
├── ANN_vs_CNN_Image_Classification.ipynb   # Google Colab Notebook
├── README.md                                # Project Documentation
├── LICENSE                                  # MIT License
```

## 📊 Datasets
- **MNIST**: 70,000 grayscale images of handwritten digits (0-9).
- **Fashion MNIST**: 70,000 grayscale images of clothing items.
- **CIFAR-10**: 60,000 RGB images across 10 object categories.

## 📌 Tasks Implemented
✅ **Dataset Preparation** - Loading, Normalization, and Reshaping.  
✅ **ANN Implementation** - Using **ReLU, Sigmoid, and Tanh** activations.  
✅ **CNN Implementation** - Experimenting with **Padding (SAME, VALID) & Stride (1,2)**.  
✅ **Hyperparameter Tuning** - Optimizing **learning rates, batch sizes, neurons, and filters**.  
✅ **Comparative Analysis** - Identifying the best-performing model for each dataset.  

---

## 🏗️ Getting Started
### 📌 Run the Notebook in Google Colab
Click below to open the notebook in Google Colab and execute it:
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aamirburma/ANN-CNN-Performance-Benchmark/blob/main/ANN_vs_CNN_Image_Classification.ipynb)

### 🖥️ Run Locally (Optional)
1. Clone this repo:
   ```bash
   git clone https://github.com/aamirburma/ANN-CNN-Performance-Benchmark.git
   cd ANN-CNN-Performance-Benchmark
   ```
2. Install required dependencies:
   ```bash
   pip install tensorflow numpy matplotlib
   ```
3. Open the notebook:
   ```bash
   jupyter notebook
   ```

---

## 📌 Results & Comparative Analysis
### **ANN Performance**
| Activation | MNIST Accuracy | FashionMNIST Accuracy | CIFAR-10 Accuracy |
|------------|---------------|-----------------|-------------|
| ReLU       | 97%           | 88%             | 72%         |
| Sigmoid    | 94%           | 85%             | 65%         |
| Tanh       | 95%           | 86%             | 68%         |

### **CNN Performance (Hyperparameter Optimized)**
| Padding | Stride | Filters | MNIST Accuracy | FashionMNIST Accuracy | CIFAR-10 Accuracy |
|---------|--------|---------|---------------|-----------------|-------------|
| SAME    | 1      | 64      | 99%           | 94%             | 80%         |
| VALID   | 2      | 32      | 97%           | 90%             | 75%         |

### **🔍 Key Findings**
✅ **CNN outperformed ANN** on complex datasets like CIFAR-10.  
✅ **ReLU activation** was the best choice for ANN.  
✅ **Padding='same' and Stride=1** resulted in the best CNN performance.  
✅ **Lower learning rates (0.0001) improved model stability** and accuracy.  

---

## 🔗 License
This project is licensed under the **MIT License**.

---

## 📌 Author & Contact
📌 **Author**: Aamirsohel Burma  
📌 **Email**: [aamirsohelburma@gmail.com](mailto:aamirsohelburma@gmail.com)  
📌 **LinkedIn**: [Connect Here](https://www.linkedin.com/in/aamirsohelburma)  

---
🔥 If you find this project useful, consider **starring ⭐ the repo** and sharing it on **LinkedIn**! 🚀
