```markdown
# GPT-Style Language Model from Scratch
### Trained on "As a Man Thinketh" by James Allen

## Overview

This project implements a **GPT-style transformer language model from scratch**
using PyTorch, trained on the classic self-help book 
*"As a Man Thinketh"* by James Allen.

The goal is not to replicate GPT-2, but to understand and implement
every component of a modern transformer-based language model from the ground up,
including tokenization, multi-head self-attention, causal masking, 
feed-forward networks, residual connections, and autoregressive text generation.

---

Built as part of a deep learning learning journey.

## Model Architecture
| Component        | Value        |
|-----------------|---------------|
| Embedding Dim   | 256           |
| Attention Heads | 8             |
| Layers          | 6             |
| Context Length  | 256 tokens    |
| Vocabulary Size | 50,257 (GPT-2)|
| Parameters      | ~18M          |

## Features
- Multi-head self-attention with causal masking
- GELU activation in feed-forward network
- Layer normalization (pre-norm style)
- Residual connections
- Top-K sampling with temperature for text generation
- Gradient clipping for stable training

## References & Acknowledgements
- Sebastian Raschka - *Build a Large Language Model From Scratch*
