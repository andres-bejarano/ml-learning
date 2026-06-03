# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

A personal ML learning repository covering neural networks with PyTorch, Hugging Face, and MLOps. Content is organized into three tracks, each with two subdirectories:
- `notebooks/` — Jupyter notebooks for exploratory learning
- `ejercicios/` — standalone Python exercise scripts

## Repository Structure

```
pytorch/        # PyTorch neural network fundamentals
huggingface/    # Hugging Face transformers and pipelines
mlops/          # MLOps tooling and workflows
```

## Common Commands

Run a Jupyter notebook server:
```bash
jupyter notebook
```

Run a Python exercise script:
```bash
python pytorch/ejercicios/<script>.py
```

Run all tests (if pytest is used):
```bash
pytest
```

## Key Conventions

- Model weights (`.pt`, `.pth`, `.h5`, `.pkl`) and `data/` and `models/` directories are gitignored — never commit large binary artifacts.
- `.ipynb_checkpoints` are gitignored.
- Each track is self-contained; exercises in `ejercicios/` should be runnable as standalone scripts.
