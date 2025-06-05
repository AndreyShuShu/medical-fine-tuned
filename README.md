# Medical GPT-Neo Fine-Tuned Model

This project demonstrates fine-tuning of the [GPT-Neo 1.3B](https://huggingface.co/EleutherAI/gpt-neo-1.3B) large language model for a medical question-answering task using the open dataset [`FreedomIntelligence/medical-o1-verifiable-problem`](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-verifiable-problem).

## 🔍 Project Description

The model is trained on 5,000 examples of open-ended medical questions with verifiable answers and evaluated on 2,000 unseen examples. Performance is measured using BLEU and ROUGE metrics.

## 🧠 Model

- **Model**: GPT-Neo 1.3B
- **Task**: Causal Language Modeling (text generation)
- **Source**: EleutherAI

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/AndreyShuShu/medical-fine-tuned
cd medical-fine-tuned
```

### 2. Install dependencies

pip install torch transformers datasets evaluate tqdm

### 3. Run the project

python project.py

⚠️ If your system does not have /mnt/d/ or /mnt/e/ paths, modify them in the script to use local paths such as ./outputs/.
