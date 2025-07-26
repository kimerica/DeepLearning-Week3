# Cancer Detection using Neural Networks

This project builds a binary classification model to detect whether a tumor is malignant or benign using a feedforward neural network. The dataset used is the Breast Cancer Wisconsin Diagnostic dataset, and the model is trained using TensorFlow/Keras.

---

## Dataset

- **Samples:** 569 observations
- **Features:** 30 numeric features (e.g., mean radius, texture, symmetry)
- **Target:** Binary label (0 = malignant, 1 = benign)

---

## Tools & Libraries

- **Language:** Python  
- **Libraries:** `TensorFlow`, `Keras`, `matplotlib`, `sklearn`, `pandas`, `numpy`

---

## Model Architecture

- Fully connected neural network (`Dense` layers)
- Activation functions: `ReLU`, `Sigmoid`
- Loss: `binary_crossentropy`
- Optimizer: `Adam`
- Metrics: `accuracy`

---

## Evaluation Metrics

- **Accuracy** (Training and Validation)
- **Loss**
- **Validation performance plots**

---

## Results

### Before Hyperparameter Tuning
- Training loss decreased steadily
- Validation loss fluctuated and spiked → **overfitting**
- Validation accuracy peaked early, then dropped

### After Hyperparameter Tuning
- Validation loss became more stable and flattened
- Training and validation accuracy aligned more closely
- Slight drop in raw accuracy but **improved generalization**

> Overall, the tuned model was more stable and reliable, even if the accuracy was marginally lower.

---

## Visualization

- Plots of training vs. validation loss
- Plots of training vs. validation accuracy over epochs

---

## How to Run

1. Clone this repository
2. Install required packages:  'pip install tensorflow scikit-learn matplotlib pandas numpy'
3. Run the notebook: `cancer-detection-nn.ipynb`

---

## Author

**Erica Kim**  
Master’s in Data Science – University of Colorado Boulder  
[GitHub Profile](https://github.com/kimerica)
