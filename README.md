# 📱 Mobile Price Range Prediction Using ANN (TensorFlow)

This project helps predict whether a mobile phone falls into the **high** or **low** price range using an Artificial Neural Network (ANN) built with TensorFlow. It’s designed to assist Nimal, a mobile manufacturer in Sri Lanka, to estimate phone prices based on features like RAM, memory, etc.

## 🧠 Model Architecture

- **Input Layer**: Based on the number of features (e.g., RAM, memory, battery)
- **Hidden Layer 1**: 8 neurons with ReLU activation
- **Hidden Layer 2**: 4 neurons with ReLU activation
- **Output Layer**: 1 neuron with sigmoid activation (binary classification)

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- Pandas
- Scikit-learn

## 📁 Dataset

Ensure you have a CSV file named `mobile_data.csv` that contains:

- Feature columns (e.g., `ram`, `internal_memory`, `battery`, etc.)
- A `price_range` column:
  - `0`: Low price range
  - `1`: High price range

## 🚀 Steps to Run

1. **Install Dependencies**
   ```bash
   pip install tensorflow pandas scikit-learn
