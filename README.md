# 🧪 Toxicity Classifier

This project is a **Toxicity Classifier** using deep learning to detect toxic behavior in comments. Built with TensorFlow and trained on a labeled dataset from Kaggle, the model aims to classify comments into different categories of toxicity.

---

## 📂 Dataset

The dataset is taken from Kaggle’s [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge), containing over 150,000 labeled comments categorized as:

- Toxic
- Severe Toxic
- Obscene
- Threat
- Insult
- Identity Hate

---

## 🧰 Technologies Used

- **Python**
- **TensorFlow / Keras**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Kaggle API**

---

## 🚀 How to Run

1. **Clone the repository**

2. **Install the required libraries**:
   ```bash
   pip install tensorflow numpy pandas matplotlib kaggle

   🧪 Model Training
The model is trained using the model.fit() method on preprocessed text data:


```bash
history = model.fit(train, epochs=1, validation_data=val)

Note: Currently set to only 1 epoch for testing. Increase epochs for better results.
