# Conversational-AI-Project

# 🤖 Question Answering with Hugging Face Transformers

Welcome to the **Question Answering** project — a simple and effective implementation of a Question Answering system using Hugging Face's `transformers` library and a fine-tuned BERT model on the SQuAD dataset.

---

## 📚 Project Overview

This project demonstrates how to build a Question Answering application using a pre-trained BERT model (`bert-large-uncased-whole-word-masking-finetuned-squad`). Given a context and a question, the model predicts the most likely answer span within the context.

---

![image alt](https://github.com/AbelPriyakumarP/Conversational-AI-Project/blob/48cd66670da23c867727c06d68293ed9e2624187/qa.png)

---

## 🚀 Features

* Uses Hugging Face's `transformers` library
* Supports custom context and question inputs
* Predicts answers using a fine-tuned BERT model
* Easily extendable for different QA datasets and models

---

## 📦 Installation

First, clone the repository:

```bash
git clone https://github.com/your-username/qa-transformer-project.git
cd qa-transformer-project
```

Then, install the required dependencies:

```bash
pip install transformers torch
```

---

## 📁 Project Structure

```
qa-transformer-project/
├── QA.ipynb                # Main notebook with QA implementation
├── README.md               # Project documentation
└── requirements.txt        # (optional) List of dependencies
```

---

## 📅 Usage

You can run the notebook directly in Jupyter:

```bash
jupyter notebook QA.ipynb
```

### Example:

* **Context**:
  *"The capital city of France is Paris. It is known for its cafes and the Eiffel Tower."*

* **Question**:
  *"What is the capital city of France?"*

* **Answer**:
  *"Paris"*

---

## 📊 Model Details

* **Model Name**: `bert-large-uncased-whole-word-masking-finetuned-squad`
* **Framework**: Hugging Face Transformers
* **Dataset**: SQuAD v1.1 (Stanford Question Answering Dataset)

---

## 📊 Future Improvements

* Add a Streamlit UI for interactive QA
* Enable multi-question batch processing
* Integrate other fine-tuned QA models
* Add evaluation metrics for performance benchmarking

---

## 📩 Contact

For any questions or suggestions, feel free to reach out:

* **Name**: Your Name
* **Email**: [your.email@example.com](mailto:your.email@example.com)
* **GitHub**: [your-username](https://github.com/your-username)

---

## 👏 Acknowledgements

* [Hugging Face Transformers](https://huggingface.co/transformers/)
* [PyTorch](https://pytorch.org/)
* [Stanford Question Answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/)
