# Math-CoT-Generator

This repository contains manually created and verified **Chain-of-Thought (CoT) solutions** for math word problems based on the GSM8K dataset.

## Purpose

The goal of this repository is to:

- Demonstrate step-by-step reasoning for math problems.
- Provide **human-readable examples** in the `samples/` folder.
- Provide **machine-readable dataset** in the `data/` folder for AI training or verification.

## Repository Structure

- `samples/` → Human-readable CoT solutions (LaTeX supported)
- `data/` → JSON dataset ready for model fine-tuning
- `verification/` → Python scripts to verify answers using SymPy
