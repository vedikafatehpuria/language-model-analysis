# Language Model Analysis (BERT and GPT-2)

This project demonstrates the use of pretrained language models (BERT and GPT-2) using HuggingFace Transformers to perform text generation and fill-mask tasks.

## Features
- BERT for masked language modeling
- GPT-2 for generative text completion
- Visual analysis of prompt confidence

## How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `jupyter notebook LM_analysis.ipynb`

## Example Use Case
```python
generator("Machine learning is", max_length=50)
