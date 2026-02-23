# Building a Language Model From Scratch

A personal project implementing a language model from the ground up to understand how modern LLMs work.

## What I'm Building

This is my journey of building a GPT-style language model by implementing each component from scratch. Rather than using high-level libraries, I'm coding the fundamental building blocks to truly understand how these models work under the hood.

## Current Progress

- [x] Tokenization and vocabulary building
- [x] Attention mechanisms (self-attention, multi-head attention)
- [x] Transformer architecture
- [x] Pretraining on unlabeled data
- [x] Text generation

## Project Structure

```
build-llm-scratch/
├── tokenizer/                      # Text tokenization and vocabulary
│   └── tokenization.ipynb
├── attention/                      # Attention mechanism implementations
│   └── attention-mechanisms.ipynb
├── pretraining_unlabelled_data/   # Model pretraining implementation
│   └── pretraining.ipynb
├── text_generation/                # Text generation with trained models
│   └── llm_from_scratch_generate_text.ipynb
└── downloads/                      # Reference materials and datasets
```

## Implementation Details

### Tokenization
Building a tokenizer from scratch to convert text into tokens that the model can process. Exploring different approaches including:
- Byte-pair encoding (BPE)
- Vocabulary creation
- Token encoding and decoding

**Notebook:** [tokenizer/tokenization.ipynb](tokenizer/tokenization.ipynb)

### Attention Mechanisms
Implementing the core attention mechanisms that power transformer models:
- Self-attention
- Multi-head attention
- Scaled dot-product attention
- Causal masking for autoregressive generation

**Notebook:** [attention/attention-mechanisms.ipynb](attention/attention-mechanisms.ipynb)

### Pretraining on Unlabeled Data
Training the GPT model on unlabeled text data:
- Data loading and preprocessing
- Training loop implementation
- Loss calculation and optimization
- Model evaluation metrics

**Notebook:** [pretraining_unlabelled_data/pretraining.ipynb](pretraining_unlabelled_data/pretraining.ipynb)

### Text Generation
Generating text using the trained language model:
- Autoregressive text generation
- Temperature scaling for controlling randomness
- Top-k and top-p sampling strategies
- Prompt-based generation

**Notebook:** [text_generation/llm_from_scratch_generate_text.ipynb](text_generation/llm_from_scratch_generate_text.ipynb)

## Technologies Used

- Python
- PyTorch
- Jupyter Notebooks
- NumPy


## Running the Code

Each component is implemented in a separate Jupyter notebook. To run:

1. Install dependencies:
```bash
pip install torch numpy jupyter matplotlib tiktoken
```

2. Open the notebooks in order:
```bash
jupyter notebook
```

3. Start with `tokenizer/tokenization.ipynb` and progress through each component.

