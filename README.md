# Llama with Python + Ollama

A beginner-friendly Jupyter Notebook project demonstrating how to run **Llama locally with Python using Ollama**.

## 🚀 Overview

This project shows how Python can communicate with a locally running Llama model through the Ollama API.

The notebook covers:

* Connecting Python to Ollama
* Sending prompts to Llama
* Controlling model temperature
* Creating multi-turn conversations
* Generating JSON responses
* Streaming responses
* Building a simple chatbot
* Creating an AI programming assistant

## 🛠️ Requirements

* Python 3.10+
* Jupyter Notebook
* Ollama
* A Llama model such as `llama3.2`

## ⚙️ Setup

Install Ollama and download the model:

```bash
ollama pull llama3.2
```

Start Ollama if it isn't already running:

```bash
ollama serve
```

Ollama's default API is available at:

```text
http://localhost:11434
```

Run the model:

```bash
ollama run llama3.2
```

Install the Python dependency:

```bash
pip install requests
```

Then open:

```text
llama_python_tutorial.ipynb
```

## 🏗️ Architecture

```text
Python / Jupyter
       │
       │ HTTP
       ▼
Ollama API
localhost:11434
       │
       ▼
   Llama Model
```

## 📚 Goal

The goal of this project is to provide a simple starting point for building **local AI applications with Python and Llama**, without requiring a paid cloud AI API.
