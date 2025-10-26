# 🧠 LLM Benchmarking Framework

A Python framework for **benchmarking multiple Large Language Models (LLMs)** across various NLP datasets and tasks — including MMLU, SQuAD, TruthfulQA, RACE, CNN/DailyMail, and more.  
Supports **OpenAI**, **Ollama**, and **Anthropic** model providers.

---

## 🚀 Features

- 📊 Evaluate multiple models across standard NLP benchmarks  
- ⚙️ Unified interface for OpenAI, Ollama, and Anthropic APIs  
- 🧮 Built-in metrics: F1, ROUGE, BLEU, Edit Distance  
- 🗂️ Dataset support via Hugging Face Datasets  
- 📄 Optional PDF summarization for research papers  
- 💾 Automatic CSV export of benchmarking results  

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/llm-benchmarking.git
cd llm-benchmarking

# Create virtual environment (optional)
python -m venv venv
source venv/bin/activate  # (or venv\Scripts\activate on Windows)

# Install dependencies
pip install -r requirements.txt
