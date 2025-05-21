
# PyTorch Tabular Classification - Binary Neural Network

This project demonstrates a simple yet effective binary classification model built using **PyTorch**. The goal is to simulate a real-world tabular classification problem, such as customer churn prediction, fraud detection, or ISR signal classification.

## 🔍 Project Overview

- **Data:** Synthetic dataset with 1,000 samples and 20 features, generated using scikit-learn.
- **Model:** Feedforward neural network (FNN) with:
  - Two hidden layers (32 → 16)
  - ReLU activations
  - Final layer outputs raw logits
- **Loss Function:** Binary Cross Entropy with Logits (`BCEWithLogitsLoss`)
- **Optimizer:** Adam
- **Training Epochs:** 30
- **Evaluation Metric:** Accuracy

## 📈 Results

- Achieved **~89% test accuracy** on unseen data.
- Model output is probabilistic, with classification threshold set at 0.5.

## 🧠 Key Skills Demonstrated

- PyTorch modeling for tabular data
- Neural network architecture design
- Training and evaluation workflows
- Binary classification with logits and probabilities

## 🗣️ Talking Points

This project mirrors real-world use cases in:
- Customer churn prediction
- Signal classification in ISR systems
- Anomaly or fraud detection in enterprise datasets

## 🚀 Next Steps

Future improvements could include:
- Model tuning with dropout and batch normalization
- Hyperparameter search
- Comparison with tree-based models (e.g., XGBoost)

---

**Created by Jake Johnson | 2025**
