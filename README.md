# 🧠 SheldonGPT: Building GPT-2 From Scratch (Inspired by The Big Bang Theory)

This project explores how to build a GPT-2-style language model entirely from scratch — without relying on Huggingface Trainer or prebuilt utilities. It’s a step-by-step educational prototype that demystifies the components of modern LLMs.

We use a custom `.txt` file made from **Sheldon Cooper’s iconic dialogue** (manually compiled) as the training dataset.

## 🔍 What’s Inside?

**Part 1 focuses on foundational steps like:**
- Loading and cleaning `.txt` data (`sheldon_dialogue.txt`)
- Tokenization & vocabulary building
- Byte-Pair Encoding (BPE) for subword units
- Special tokens (e.g., `<|endoftext|>`, `<|unk|>`)
- Sliding window sampling of text sequences
- Token embeddings (`[batch, sequence_length, embedding_size]`)

The goal is to walk through every step, from raw text to a trainable input format.

---

## 📁 Files
- `sheldon data v2.ipynb` – full pretraining script from scratch
- `sheldon_dialogue.txt` – Text corpus used for training
- `README.md` – You’re reading it

## 🤓 Why Do This?

To understand how transformers work *under the hood* — from first principles. No black boxes.

---

## 🚀 Coming Soon (Part 2)

In **Part 2**, we’ll dive into:
- Self-attention (from scratch)
- Multi-head attention layers
- Transformer blocks (layer norm, MLPs, GELU)
- Model configs (vocab size, heads, layers, etc.)
- Training loop and decoding strategies (temp, top-k sampling)

---

## 📖 Read the LinkedIn Article  
👉 [https://www.linkedin.com/posts/emmanuel-ochiba_built-my-own-gpt-2-model-from-scratch-using-activity-7351240765139783680-8_cd?utm_source=share&utm_medium=member_desktop&rcm=ACoAADUBMK0BJKnDNOJm8Uyny8EmQ_c2UBVsWCc]

## ⭐️ Star this repo if you enjoy the project or learn something new!
