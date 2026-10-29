# 📝 Text Summarizer

A web-based **Text Summarization Application** built using FastAPI, Hugging Face Transformers, and the T5 model. It allows users to enter or paste text and generate concise summaries through a simple web interface.

## 🚀 Features

* Automatic text summarization using T5
* Simple and user-friendly web interface
* FastAPI backend for processing requests
* PyTorch-powered model inference

## 🛠️ Tech Stack

* Python
* FastAPI
* Hugging Face Transformers
* T5 Model
* PyTorch
* HTML, CSS, JavaScript

## ⚙️ Installation

```bash
git clone https://github.com/PRATUSH02/text-summarizer.git
cd text-summarizer
pip install -r requirements.txt
uvicorn app:app --reload
```

Before running, ensure your trained or downloaded model and tokenizer are available in the `saved_summary_model/` directory.

## 📌 API Endpoint

`POST /summarize/`

Accepts text as JSON and returns the generated summary.

## 👨‍💻 Author

Developed as an AI/NLP project to explore transformer-based text summarization .
