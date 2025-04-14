### English to Igbo Machine Translation (NMT)

This project implements a **Neural Machine Translation** system for **low-resource languages**, specifically translating from **English to Igbo**.

It explores various RNN-based architectures (LSTM, GRU), incorporates **attention mechanisms**, and evaluates **transfer learning** using MarianMT (Helsinki NLP).

---

## 📌 Key Features

- Seq2Seq Model with **Attention Mechanism**  
- Comparison between **LSTM vs GRU**  
- **BLEU Score** evaluation  
- **Transfer learning** with MarianNMT  
- Tokenization, preprocessing, and vocabulary building  
- Experiments with **decoding strategies** (Greedy, Beam Search)

---

## 📁 Project Structure

```
/data               - Parallel English-Igbo corpus  
/preprocessing      - Tokenization & cleaning scripts  
/models             - RNN, GRU, and MarianMT models  
/evaluation         - BLEU, loss curves, and performance metrics  
notebooks/          - Training & inference Jupyter notebooks  
```

---

## 🚀 How to Run

1. Clone the repo  
2. Install requirements from `requirements.txt`  
3. Run preprocessing:  
   `python preprocess.py`  
4. Train the model:  
   `python train_seq2seq.py`

---

## 📊 Results

- Achieved BLEU score: **~70%** on clean sentence pairs  
- **+4.83 BLEU** improvement using transfer learning (MarianMT)  
- Strong performance with attention-based decoder

---

## 🤝 Acknowledgments

- Dataset: Open English-Igbo parallel corpora  
- Libraries: PyTorch, HuggingFace, NLTK, MarianMT
