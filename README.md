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
---
## 🚀 Quickstart (Run Locally)

Follow the steps below to run the project on your local machine.

---

### 1.Clone the repository

```bash
git clone https://github.com/sairitvikb/RNN-IMDB-System.git
cd RNN-IMDB-System
```

---

### 2. Create and Activate a Virtual Environment (Recommended)

#### Windows (PowerShell)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

#### macOS / Linux

```bash
python3 -m venv .venv
source .venv/bin/activate
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Run the Streamlit Application

```bash
streamlit run main.py
```

Once the application starts, your default browser will open automatically.

You can then:
- Enter a movie review in the input box
- Click **Classify**
- View the predicted sentiment (Positive or Negative)

---

You are now ready to use the RNN IMDB Sentiment Analysis System locally.
