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
## 🚀 Quickstart (Run Locally)

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sairitvikb/RNN-IMDB-System.git
cd RNN-IMDB-System
```

---

### 2️⃣ Create & Activate a Virtual Environment (Recommended)

#### 🪟 Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

#### 🍎 macOS / 🐧 Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the Streamlit Application

```bash
streamlit run main.py
```

After running the command, your browser will open automatically.

Simply:
- Paste a movie review
- Click **Classify**
- View the predicted sentiment (Positive / Negative)

---

✅ You’re now ready to test the RNN IMDB Sentiment Analysis System!
