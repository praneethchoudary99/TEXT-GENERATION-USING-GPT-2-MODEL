# Fine-Tuning GPT-2 on Custom Text Data
Generative AI Internship Project

## 📌 Project Overview

This project demonstrates how to **load, preprocess, and fine-tune the GPT-2 model** on a small custom text dataset using the **Hugging Face Transformers** library and **PyTorch**.

The project covers the complete basic workflow of:
- loading a pretrained GPT-2 tokenizer and model,
- preparing custom text data,
- tokenizing the dataset,
- creating a PyTorch dataset class,
- adjusting tokenizer padding settings,
- resizing model embeddings,
- and initializing the Hugging Face `Trainer` for fine-tuning.

This project is useful for understanding the fundamentals of **custom language model fine-tuning** in Generative AI.

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- GPT-2 Pretrained Model
- Trainer API

---

## ⚙️ Features

- Loads pretrained **GPT-2 tokenizer and model**
- Creates a **custom text dataset**
- Tokenizes text data for training
- Builds a **PyTorch Dataset class**
- Adds **pad token support** for GPT-2
- Resizes model embeddings after tokenizer adjustment
- Configures training using **TrainingArguments**
- Initializes Hugging Face **Trainer** for fine-tuning

---

## 📦 Installation

Install the required libraries:

```bash
pip install transformers torch datasets
