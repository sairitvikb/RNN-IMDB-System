# RNN-IMDB-System 🎬🧠  
A simple **IMDB movie review sentiment analysis** app built with **TensorFlow/Keras (SimpleRNN)** and deployed as a **Streamlit** web UI.

This project loads a pre-trained RNN model and classifies a user-entered review as **Positive** or **Negative**. 

---

## ✨ Features
- **Streamlit UI** to paste/type a movie review and classify it instantly  
- Uses the built-in **Keras IMDB dataset word index** for text encoding :contentReference[oaicite:2]{index=2}  
- Pads sequences to a fixed length (maxlen = 500) before inference :contentReference[oaicite:3]{index=3}  
- Loads a saved Keras model file: `simple_rnn_imdb.h5` :contentReference[oaicite:4]{index=4}  

---

## 🧰 Tech Stack
- Python
- TensorFlow / Keras :contentReference[oaicite:5]{index=5}
- NumPy, Pandas, Scikit-learn :contentReference[oaicite:6]{index=6}
- Streamlit :contentReference[oaicite:7]{index=7}

---

## 📁 Project Structure
```text
.
├── main.py                # Streamlit app + preprocessing + inference
├── simplernn.ipynb         # Training / experimentation notebook
├── prediction.ipynb        # Prediction/testing notebook
├── simple_rnn_imdb.h5      # Saved trained model
└── requirements.txt        # Dependencies
