# Handwritten-Digit-Recognition-using-CNNs-on-MNIST-TensorFlow-Keras-
Built a CNN-based handwritten digit recognition model using TensorFlow and Keras on the MNIST dataset. Performed data preprocessing, normalization, and model optimization with dropout and early stopping. Achieved ~98–99% accuracy with strong generalization and evaluation metrics.
# Handwritten Digit Recognition using CNN (TensorFlow & Keras)


This project builds a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset, a standard benchmark in computer vision. The model learns visual patterns from 70,000 grayscale digit images and achieves high prediction accuracy on unseen data.

---

## 📊 Dataset
- **MNIST Dataset**
- 70,000 images (60k training, 10k testing)
- 28×28 pixels, grayscale
- 10 classes (digits 0–9)

---

## 🧠 Model Architecture
- Convolutional layers for feature extraction  
- Max Pooling for spatial dimensionality reduction  
- Dense layers for classification  
- Softmax output layer for multi-class prediction  
- Dropout + Batch Normalization to reduce overfitting  

---

## 🔧 Tech Stack
| Category | Tools |
|---------|------|
| Programming | Python |
| Deep Learning | TensorFlow, Keras |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |

---

## 🚀 Implementation Steps
1. Data preprocessing (normalization, reshaping)
2. Train/validation split for generalization testing
3. Model training using Adam optimizer + cross-entropy loss
4. Evaluation with accuracy, confusion matrix, and learning curves

---

## 📈 Performance
- **Accuracy:** ~98–99%
- Robust evaluation on unseen test data
- Strong generalization and low error rate

---

## 📌 Results Visualization
- Training vs Validation Accuracy/Loss curves
- Confusion Matrix for class-wise performance
- Sample predictions for model interpretation

---

## 🏁 Future Improvements
- Data augmentation to boost robustness
- CNN hyperparameter tuning
- Model deployment using Streamlit/Flask
- Testing advanced architectures (ResNet, MobileNet)

---

## 🤝 Contributions
Pull requests and suggestions are welcome!

---

## 📬 Contact
For queries or collaboration:
- **GitHub:** https://github.com/Shahzadhussain2005
- **Email:** shahzadhussain9680@gmail.com

---
