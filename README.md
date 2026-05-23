# 📝 Next Word Prediction 

A Deep Learning and Natural Language Processing ( NLP ) project that predicts the next word in a sentence using an LSTM ( Long Short Term Memory ) neural network.

This project demonstrates how language models work behind text autocomplete systems such as smartphone keyboards, search engines, and writing assistants. The model is trained on text data, learns sequential word patterns, and predicts the most probable next word based on user input.

---

## 🚀 Project Overview

Next Word Prediction is a language modeling task where the model predicts the next word in a sequence of text.

Example:

Input:
```text
the meaning of
```

Prediction:
```text
life
```

The project covers the complete NLP workflow:

- Text preprocessing
- Tokenization
- Sequence generation
- Padding
- LSTM model building
- Training and evaluation
- Next word prediction

---

## ✨ Features

✅ Text preprocessing and cleaning  
✅ Tokenization using NLP techniques  
✅ Sequence generation for language modeling  
✅ Deep Learning model using LSTM  
✅ Predicts next word from input text  
✅ End to end notebook implementation  

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- TensorFlow / Keras
- NumPy
- NLP preprocessing tools

---

## 📂 Project Structure

```text
next-word-prediction/
│
├── app.py
├── lstm_model.h5
├── tokenizer.pkl
├── max_len.pkl
├── qoute_dataset.csv
├── main.ipynb
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/kaushal033/next-word-prediction.git
```

Move into the project directory:

```bash
cd next-word-prediction
```

Create and activate a virtual environment (recommended):

### Conda

```bash
conda create -n nextword python=3.11 -y
conda activate nextword
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook and run all cells:

```bash
jupyter notebook
```

The workflow includes:

1. Loading and preprocessing text data  
2. Creating word sequences  
3. Training the LSTM model  
4. Saving the trained model  
5. Generating next word predictions  

Example:

```python
seed = "the meaning of life"
generate_text(model, tokenizer, seed)
```

---

## 🧠 Model Architecture

The project uses an **LSTM based Recurrent Neural Network ( RNN )** for sequence prediction.

Typical pipeline:

```text
Embedding Layer
        ↓
LSTM Layer(s)
        ↓
Dense Layer
        ↓
Softmax Output
```

LSTM networks are particularly effective for language modeling because they capture contextual and sequential relationships between words.

---

## 📊 How It Works

The model learns from text sequences.

Example sentence:

```text
I love machine learning
```

Generated sequences:

```text
I → love
I love → machine
I love machine → learning
```

After training, the model predicts the most likely next word from learned patterns.

---

## 🎯 Applications

This type of model can be used in:

- Text autocomplete
- Smart keyboards
- Search suggestions
- Writing assistants
- Chatbots
- NLP research projects

---

## 📈 Future Improvements

Possible enhancements:

- Train on larger datasets
- Use Bidirectional LSTM
- Add GRU or Transformer models
- Improve prediction accuracy with larger embeddings

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository  
2. Create a new branch  
3. Commit your changes  
4. Push to GitHub  
5. Open a Pull Request

If you found this project helpful, consider giving it a ⭐ on GitHub.
