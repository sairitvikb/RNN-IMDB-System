# RNN-IMDB-System 🎬🧠  
A simple **IMDB movie review sentiment analysis** app built with **TensorFlow/Keras (SimpleRNN)** and deployed as a **Streamlit** web UI.

This project loads a pre-trained RNN model and classifies a user-entered review as **Positive** or **Negative**. 

---

## ✨ Features
- **Streamlit UI** to paste/type a movie review and classify it instantly  
- Uses the built-in **Keras IMDB dataset word index** for text encoding   
- Pads sequences to a fixed length (maxlen = 500) before inference  
- Loads a saved Keras model file: `simple_rnn_imdb.h5`

---

## 🧰 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas, Scikit-learn
- Streamlit 

---

## 📁 Project Structure
```text
.
├── main.py                # Streamlit app + preprocessing + inference
├── simplernn.ipynb         # Training / experimentation notebook
├── prediction.ipynb        # Prediction/testing notebook
├── simple_rnn_imdb.h5      # Saved trained model
└── requirements.txt        # Dependencies
