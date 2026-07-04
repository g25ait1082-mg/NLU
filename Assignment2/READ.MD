# Sanskrit-to-English Neural Machine Translation

**Student Name:** Madhu Garg

## Course
Natural Language Understanding

## Assignment
Assignment 2: Sanskrit-to-English Neural Machine Translation

---

## Project Overview

This project implements a custom Sequence-to-Sequence (Seq2Seq) Neural Machine Translation model with an attention mechanism to translate Sanskrit sentences into English using PyTorch.

The model is trained using the provided Sanskrit-English parallel corpus.

---

## Project Structure

```
.
├── Assignment2_Madhu_Garg.ipynb
├── submission.csv
├── requirements.txt
├── README.md
├── best_seq2seq_model.pth
└── training_curve.png
```

---

## Features

- Custom Seq2Seq Architecture
- GRU Encoder
- GRU Decoder
- Bahdanau Attention
- Teacher Forcing
- Gradient Clipping
- BLEU Evaluation
- BERTScore Evaluation
- Inference Time Measurement
- Model Parameter Count

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Running the Notebook

Open

```
Assignment2_Madhu_Garg.ipynb
```

Run every cell sequentially.

---

## Evaluation Metrics

- BLEU Score
- BERTScore
- Inference Time
- Trainable Parameters

---

## Output

The notebook generates

- submission.csv
- training_curve.png
- BLEU Score
- BERTScore

---

## Libraries Used

- PyTorch
- NumPy
- Pandas
- Matplotlib
- NLTK
- bert-score

---

## Author

Madhu Garg