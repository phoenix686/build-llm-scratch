# Building a Language Model From Scratch

A personal project implementing a language model from the ground up to understand how modern LLMs work.

## What I'm Building

This is my journey of building a GPT-style language model by implementing each component from scratch. Rather than using high-level libraries, I'm coding the fundamental building blocks to truly understand how these models work under the hood.

## Current Progress

- [x] Tokenization and vocabulary building
- [x] Attention mechanisms (self-attention, multi-head attention)
- [ ] Transformer architecture
- [ ] Training pipeline
- [ ] Text generation

## Project Structure

```
build-llm-scratch/
├── tokenizer/           # Text tokenization and vocabulary
├── attention/           # Attention mechanism implementations

```

## Implementation Details

### Tokenization
Building a tokenizer from scratch to convert text into tokens that the model can process. Exploring different approaches including byte-pair encoding (BPE).

### Attention Mechanisms
Implementing the core attention mechanisms that power transformer models:
- Self-attention
- Multi-head attention
- Scaled dot-product attention

### Next Steps
- Complete the full transformer architecture
- Implement the training loop
- Test on text generation tasks

## Requirements

```
python >= 3.10
pytorch
jupyter
numpy
matplotlib
```

## Running the Code

The implementation is primarily in Jupyter notebooks for experimentation and visualization:

```bash
jupyter lab
```

Then navigate to the relevant notebooks in `tokenizer/` or `attention/` folders.


