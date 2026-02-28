# LLM Hallucination Lab

This repository demonstrates how large language models (LLMs) can confidently generate incorrect information — a phenomenon known as **hallucination**.

## What This Is

This is a simple chatbot experiment built using a small open-source language model.  
The goal is to show how models generate responses based on probability rather than verified knowledge.

The bot may:
- Provide plausible but incorrect answers
- Invent facts
- Answer confidently even when wrong

This behavior is not a bug — it is a natural consequence of next-token prediction.

## Why This Matters

As LLMs become more integrated into education, research, and decision-making, understanding hallucination becomes critical.

This repository is designed for:
- AI students
- Educators
- Researchers
- Anyone curious about how LLMs actually behave

## How It Works

The model predicts the next most likely token based on training data patterns.
It does not "know" facts.
It generates text that statistically fits the prompt.

This demo intentionally runs without external retrieval (no RAG) to highlight pure model behavior.

## Installation

```bash
pip install torch transformers
