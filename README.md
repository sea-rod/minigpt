# 🧠 MiniGPT

**MiniGPT** is a minimalist GPT-style Transformer language model trained on Shakespeare's works. It uses **Byte Pair Encoding (BPE)** for tokenization and demonstrates how to build and train a transformer decoder from scratch using PyTorch.

---

## 📚 Overview

This project is an educational implementation of the GPT architecture, focusing on:

* Training a small transformer model on Shakespearean text
* Implementing BPE tokenization from scratch
* Understanding the internals of attention, positional encoding, and transformer blocks

---

## 🔧 Model Configuration

* **Tokenizer**: Byte Pair Encoding (BPE)
* **Vocabulary Size**: `10,000`
* **Embedding Dimension**: `128`
* **Number of Attention Heads**: `4`
* **Number of Transformer Blocks**: `4`
* **Training Data**: Complete works of William Shakespeare

---

## 🗂️ Project Structure

```
.
├── decoder.ipynb       # Main notebook for tokenizer, model, training and generation
└── input.txt           # Shakespeare training corpus
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/mini-gpt.git
cd mini-gpt
```

### 2. Install Dependencies

Ensure you have Python 3.8+ and PyTorch installed. Then install any other dependencies:

```bash
pip install torch numpy tqdm
```

### 3. Run the Notebook

Open the notebook:

```bash
jupyter notebook decoder.ipynb
```

Follow through the cells to:

* Train the BPE tokenizer
* Encode the Shakespeare text
* Train the transformer decoder model
* Generate text from a prompt

---

## 💬 Text Generation

Once the model is trained, you can generate Shakespeare-style text by providing a prompt and sampling from the model's output logits.

---

## 📈 Future Improvements

* Add a CLI for training and generation
* Support saving/loading model checkpoints
* Expand to GPT-2 style architecture with multi-layer norms
* Train on larger datasets

---

## ✍️ Author

Developed by Seamus .F. Rodrigues
