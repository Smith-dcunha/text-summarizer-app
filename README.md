# AI Text Summarizer

An AI-powered dialogue text summarization web application built using a fine-tuned T5 Transformer model and FastAPI.

## Overview

This project converts long conversations or dialogues into concise summaries using a fine-tuned T5 sequence-to-sequence model.

The application provides a simple web interface where users can enter a dialogue and receive an automatically generated summary.

## Features

- AI-powered dialogue summarization
- Fine-tuned T5 Transformer model
- FastAPI backend
- Interactive web interface
- REST API endpoint for summarization
- Automatic preprocessing of dialogue text
- Support for CPU, CUDA, and Apple Silicon MPS devices

## Tech Stack

- **Python**
- **T5 Transformer**
- **Hugging Face Transformers**
- **PyTorch**
- **FastAPI**
- **Jinja2**
- **HTML/CSS**

## Project Structure

```text
text-summarizer-app/
│
├── app.py
├── index.html
├── requirements.txt
├── README.md
├── .gitignore
└── saved_summary_model/