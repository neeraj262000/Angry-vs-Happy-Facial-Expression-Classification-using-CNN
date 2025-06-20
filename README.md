# Angry vs Happy Facial Expression Classification using CNN

This project demonstrates the use of a Convolutional Neural Network (CNN) for classifying facial expressions into two categories: **Angry** and **Happy**. It utilizes image data, processes it using deep learning techniques, and evaluates the model's performance using relevant metrics.

## 📁 Project Structure

```
├── Angry - Happy Classification using CNN.ipynb
├── README.md
└── dataset/
    ├── train/
    │   ├── Angry/
    │   └── Happy/
    └── test/
        ├── Angry/
        └── Happy/
```

## 🧠 Model Overview

- **Architecture**: Convolutional Neural Network
- **Framework**: TensorFlow / Keras
- **Layers**:
  - Multiple `Conv2D` + `MaxPooling2D`
  - `Flatten`
  - `Dense` layers with dropout
  - Final layer with `sigmoid` activation (binary classification)

## 📊 Metrics Used

- **Accuracy**
- **Loss**
- **Confusion Matrix**
- **Precision, Recall, F1-Score**

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/angry-happy-classification.git
   cd angry-happy-classification
   ```

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure dataset is structured correctly (as shown above).

4. Run the notebook:
   ```bash
   jupyter notebook "Angry - Happy Classification using CNN.ipynb"
   ```

## ✅ Requirements

- Python 3.7+
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn

You can generate the `requirements.txt` using:
```bash
pip freeze > requirements.txt
```

## 📷 Sample Output

The model outputs performance graphs and prediction results for both angry and happy images.

## 📌 Future Improvements

- Use a larger and more diverse dataset.
- Apply data augmentation techniques.
- Experiment with different CNN architectures (e.g., ResNet, MobileNet).
- Deploy the model with a web interface.

## 🧑‍💻 Author

- **Your Name** – [@yourGitHub](https://github.com/yourGitHub)
