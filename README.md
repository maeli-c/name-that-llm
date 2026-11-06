# Kaggle-Name-That-LLM
Name that LLM Kaggle challenge solution from three THU CS students (aka team MAMAHE)

## Overview

This repository contains the code and notebooks used to participate in the Kaggle LLM challenge. The goal is to build a competitive solution while keeping the workflow reproducible and well-documented.

> **Competition link**: *(add the Kaggle competition URL here)*

## Quick Start

```bash
# Clone the repository
git clone https://github.com/<your-username>/llm-kaggle-challenge.git
cd llm-kaggle-challenge

# Install dependencies
pip install -r requirements.txt

# Download competition data (requires Kaggle API key configured)
kaggle competitions download -c <competition-slug> -p data/raw

# Run the submission pipeline
python src/predict.py
