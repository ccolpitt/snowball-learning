# Snowball Learning

The goal is to learn the basics of pytorch and other basic libraries, so that I (and others) can get an intuitive understanding of how the primitive building blocks work - so that I can design and train superhuman policies. Each notebook is a self-contained experiment building toward world models, RL, and neural plasticity. Starting with raw PyTorch mechanics — no wrappers, no vibe coding.

## Roadmap

```
Level 1: PyTorch Foundations          ← Current
  └── Tensor mechanics, autograd, strides
Level 2: Core Blocks
  └── Attention, KV cache, transformers from scratch
Level 3: Connect 4 World Model
  └── Train agent that predicts game states
Level 4: Continual Learning & Plasticity
  └── Dynamic pruning, structural growth, neuro-circuits
```

## Structure

Each topic gets its own folder with a notebook:

```
01-tensor-strides/tensor_memory.ipynb
02-autograd/autograd_mechanics.ipynb
03-attention/raw_attention.ipynb
...
```

## Setup

```bash
pip install -r requirements.txt
```
