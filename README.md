# AI_Journey
A collection of beginner-friendly AI and NLP projects built with PyTorch, Transformers, and Gradio, including a character-level joke generator, a DistilBERT joke classifier, and a PDF question-answering chatbot powered by Groq LLMs.

# AI Mini Projects Collection

This repository contains three beginner-friendly AI and NLP projects built using PyTorch, Hugging Face Transformers, and Gradio.

The purpose of these projects is to explore the fundamentals of:
- Neural Networks
- Natural Language Processing (NLP)
- Transformer Models
- Text Generation
- Text Classification
- LLM-based Applications

---

# Projects Included

## 1. Character-Level Joke Generator

A simple neural network trained on a small dataset of jokes to generate new jokes character by character.

### Features
- Custom character tokenizer
- PyTorch neural network
- Embedding layers
- Joke generation using probabilistic sampling
- Lightweight and beginner-friendly implementation

### Technologies Used
- Python
- PyTorch

### Example Output

```text
why did the banana go to school? because it wasnt peeling well!
```

### How It Works
- The text dataset is converted into character-level tokens
- Characters are mapped into embeddings
- The neural network predicts the next character
- Generated characters are combined to create jokes

---

## 2. Joke vs Non-Joke Classifier

A text classification project using DistilBERT to determine whether a sentence is a joke or not.

### Features
- Hugging Face Transformers
- DistilBERT fine-tuning
- Custom labeled dataset
- Real-time sentence classification
- Simple NLP training pipeline

### Technologies Used
- Python
- PyTorch
- Transformers
- Hugging Face Trainer API

### Example Predictions

```text
Input: "what do you call a bear with no teeth? a gummy bear!"
Prediction: JOKE

Input: "the traffic today was really bad"
Prediction: NOT A JOKE
```

### How It Works
- Text data is tokenized using DistilBERT tokenizer
- A transformer model is fine-tuned on labeled examples
- The model predicts whether input text is a joke or normal text

---

## 3. PDF Question Answering Bot

An AI-powered chatbot that allows users to upload a PDF and ask questions about its contents.

### Features
- PDF text extraction
- Conversational question answering
- Groq LLM integration
- Interactive Gradio interface
- Multi-turn conversation support

### Technologies Used
- Python
- Gradio
- Groq API
- PyPDF

### Use Cases
- Research papers
- Study notes
- Documentation
- Reports
- Educational material

### How It Works
- Users upload a PDF file
- Text is extracted from all pages
- The extracted text is sent as context to the LLM
- Users can ask questions related to the document

---

# Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Requirements

Main libraries used in this repository:

```text
torch
transformers
datasets
gradio
groq
pypdf
```

You can install them manually:

```bash
pip install torch transformers datasets gradio groq pypdf
```

---

# Running the Projects

## Run Joke Generator

```bash
python joke_generator.py
```

---

## Run Joke Classifier

```bash
python joke_classifier.py
```

---

## Run PDF Q&A Bot

```bash
python app.py
```

---

# Project Structure

```text
AI-Mini-Projects/
│
├── joke_generator.py
├── joke_classifier.py
├── app.py
├── requirements.txt
└── README.md
```

---

# Learning Objectives

These projects help in understanding:
- Deep learning basics
- NLP preprocessing
- Tokenization
- Transformer fine-tuning
- Text generation
- Sequence classification
- Prompt engineering
- Building AI interfaces
- Working with APIs and LLMs

---

# Future Improvements

Some possible future enhancements:
- Larger datasets for training
- Better joke generation quality
- Improved model accuracy
- Retrieval-Augmented Generation (RAG)
- Vector database integration
- Conversation memory
- Deployment support
- Better UI and user experience

---

# License

This project is open-source and available under the MIT License.
