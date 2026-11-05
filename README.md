# Pretrained Transformer Models & NLP Applications

## Overview

This repository contains practical implementations of pretrained Transformer-based language models and Large Language Models (LLMs) using Python.

The objective is to understand how pretrained models can be integrated into real-world Natural Language Processing (NLP) applications without training neural networks from scratch.

The implementations explore model loading, tokenization, inference, text generation, sentiment classification, text summarization, and autoregressive language modeling using PyTorch, Hugging Face Transformers, and Ollama.

## Implementations

| No. | Implementation | Technology / Model |
|---|---|---|
| 1 | Pretrained BERT Sentiment Analysis | DistilBERT, PyTorch |
| 2 | Pretrained T5 Text Summarization | FLAN-T5 Small |
| 3 | GPT-2 Text Generation | GPT-2 |
| 4 | DistilGPT-2 Text Generation | DistilGPT-2 |
| 5 | Autoregressive Language Generation | Hugging Face Transformers |
| 6 | Local LLM Chatbot | Llama 3.2 (1B), Ollama |

### 1. Pretrained BERT Sentiment Analysis
- Uses a pretrained DistilBERT sentiment classification model.
- Performs positive and negative sentiment classification.
- Explores tokenization, input IDs, logits, and softmax probabilities.
- Displays predicted labels and confidence scores.

### 2. Pretrained T5 Text Summarization
- Uses Google's FLAN-T5 Small model.
- Converts text summarization into an instruction-based NLP task.
- Uses encoder-decoder architecture.
- Implements beam search for summary generation.

### 3. GPT-2 Text Generation
- Uses a pretrained GPT-2 language model.
- Demonstrates autoregressive text generation.
- Explores prompt-based language modeling.

### 4. DistilGPT-2 Text Generation
- Uses the pretrained DistilGPT-2 model.
- Inspects next-token logits and probability distributions.
- Compares greedy decoding and sampling.
- Explores temperature and top-k sampling strategies.

### 5. Autoregressive Language Generation
- Demonstrates next-token prediction using a pretrained language model.
- Explores prompt-based generation through the Transformers pipeline.
- Examines how generated sequences extend the input prompt.

### 6. Local LLM Chatbot
- Integrates the Llama 3.2 (1B) model through Ollama.
- Implements an interactive command-line chatbot.
- Uses conversational prompts and system instructions.
- Demonstrates local LLM inference.

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Tokenizers
- Ollama
- Natural Language Processing (NLP)
- Large Language Models (LLMs)

## Project Structure

```text
Pretrained-Transformer-Models/
│
├── 4_Pretrained_BERT_Sentiment_Analysis.py
├── 5_Pretrained_T5_Text_Summarization.py
├── 6_LLm_Autoregressive.py
├── 7_LLM_Chatbot.py
├── DistilGPT2_Text_Generation.py
├── GPT2_Text_Generation.py
│
├── requirements.txt
└── README.md
```

*Adjust the filenames in this structure to match the actual files you upload.*

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/aartiwamane/Pretrained-Transformer-Models.git
```

### 2. Navigate to the project directory

```bash
cd Pretrained-Transformer-Models
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run an implementation

For example:

```bash
python 4_Pretrained_BERT_Sentiment_Analysis.py
```

```bash
python 5_Pretrained_T5_Text_Summarization.py
```

## Model Downloads

The implementations use pretrained models available through Hugging Face.

Models are automatically downloaded when `from_pretrained()` is called for the first time. An internet connection is required for the initial download.

The chatbot implementation requires Ollama to be installed separately, with the Llama 3.2 (1B) model available locally.

## Learning Outcomes

- Understanding pretrained Transformer architectures.
- Working with tokenizers and contextual representations.
- Understanding logits, probability distributions, and confidence scores.
- Exploring encoder-only, encoder-decoder, and decoder-only models.
- Implementing text generation and summarization.
- Comparing greedy decoding, beam search, and sampling.
- Building an interactive chatbot using a locally running LLM.

## Author

**Aarti Wamane**

M.Tech Computer Engineering | Python | Machine Learning | Deep Learning | NLP | Generative AI

GitHub: https://github.com/aartiwamane

LinkedIn: https://linkedin.com/in/aarti-wamane-5276562a6

---

*This repository is intended for educational purposes and practical exploration of pretrained language models and Transformer-based NLP applications.*
