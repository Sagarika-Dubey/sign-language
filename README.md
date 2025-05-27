# 🤟 ASL Sign Language Recognition

A real-time American Sign Language (ASL) alphabet recognition system using Convolutional Neural Networks (CNN). This project uses computer vision and deep learning to classify ASL gestures captured via webcam, aiming to enhance accessibility for the hearing-impaired.

---

## 📹 Demo

[🔗 Watch Demo](https://drive.google.com/file/d/1I0NkM7ky7cTXcl2iqjrFZNCkIx7HstLp/view?usp=sharing)  

---

## 🧠 Features

- Real-time ASL alphabet recognition using webcam input
- Custom CNN built with TensorFlow/Keras
- Trained on the ASL Alphabet dataset (dataset is self-made)
- Live gesture prediction with OpenCV
- Easy-to-use and extendable for more gestures

---

## 🚀 Tech Stack

- **Python**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy / Matplotlib**
- **Jupyter Notebook**

---

## 📂 Project Structure
```
sign-language/
├── asl_alphabet_train/ # Training images (A-Z)
├── model/ # Saved model (H5)
├── Sign_Language_CNN.ipynb # Model training notebook
├── real_time_prediction.py # Real-time webcam gesture prediction
└── README.md
```

## 🏁 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Sagarika-Dubey/sign-language.git
cd sign-language
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run Real-Time Prediction
```bash
python app.py
```

