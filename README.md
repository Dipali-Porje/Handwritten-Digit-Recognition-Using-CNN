# ✍️ Handwritten Digit Recognition using CNN with Tkinter GUI

This project is a desktop-based handwritten digit recognition system powered by a **Convolutional Neural Network (CNN)**. It takes an image of a handwritten digit as input and predicts a number between **0 and 9**. A simple and interactive **Tkinter GUI** is included for ease of use.

---

## 🔢 Digits Recognized

- `0` to `9` — Recognized from handwritten images
- Trained on the popular **MNIST** dataset (60,000 training + 10,000 testing images)

---

## 🧠 Model Overview

- Model Type: **CNN (Convolutional Neural Network)**
- Dataset: **MNIST**
- Framework: **TensorFlow / Keras**
- Input Size: **28x28 grayscale**
- Output: Digit class (0–9) with confidence score

---

## 🖥️ Tkinter GUI Features

- 📂 Upload a handwritten digit image (JPG/PNG)
- 🎯 Predict the digit in real time
- 📊 Display prediction and confidence
- 🔄 Option to reset and upload another image

---

## 🗂️ Project Structure

digit_recognition_gui/
├── digit_model.h5 # Trained CNN model
├── prediction.ipynb
├── digit_recognition.ipynb
├── requirements.txt
└── README.md


---

## 🚀 How to Run the App

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/Dipali-Porje/Handwritten-Digit-Recognition-Using-CNN.git
cd Handwritten-Digit-Recognition-Using-CNN

---

## 🚧 Future Enhancements

Draw a digit using mouse in the GUI and predict in real-time
Add support for mobile or web-based prediction using Flask/Streamlit
Add heatmap to visualize important regions of prediction


