# VisionNet-X: CNN Architectures & Transfer Learning Performance Comparison

This project evaluates four different Convolutional Neural Network (CNN) architectures to understand how model depth, regularization, and transfer learning affect image classification accuracy on the Imagenette dataset.

## 📌 Models Compared
1. **Basic CNN**
2. **All-CNN Architecture**
3. **Regularized CNN**
4. **Transfer Learning Model (Pretrained Network)**

---

## 🚀 Objective
The goal is to compare traditional CNN models with more advanced techniques such as regularization and transfer learning to determine which architecture provides the highest accuracy and most stable training behavior.

---

## 📊 Results Summary

| Model | Test Accuracy | Notes |
|-------|--------------|-------|
| Basic CNN | 70.52% | Baseline, slight overfitting |
| All-CNN Model | 70.70% | Early stopping triggered |
| Regularized CNN | 70.97% | More stable, less overfitting |
| **Transfer Learning** | **80.87%** | Best performance, strong generalization |

---

## 🧠 Key Insights
- Transfer learning significantly improves performance by leveraging pretrained features.
- Regularization techniques help stabilize training and reduce overfitting.
- All simple CNN models plateau around ~70% accuracy.
- Transfer learning achieves **10% higher accuracy**, showing the power of pretrained deep networks.

---

## 🛠️ Technologies Used
- Python  
- PyTorch  
- Convolutional Neural Networks  
- Regularization (Dropout, etc.)  
- Transfer Learning (fine-tuning pretrained models)

---

## 📈 Training Logs (Highlights)
### Basic CNN
- Test Accuracy: 70.52%
- Validation loss fluctuates → overfitting likely

### All-CNN
- Early stopping after 5 epochs
- Test Accuracy: 70.70%

### Regularized CNN
- More stable validation performance
- Test Accuracy: 70.97%

### Transfer Learning
- Best model: Test Accuracy **80.87%**
- Consistent drop in training & validation loss

---

## 🏆 Best Model
### ✔ **Transfer Learning Model**
Achieved the highest test accuracy (80.87%) and demonstrated strong generalization.

These weights are recommended for deployment or further experimentation.

