# WiDS 2025–26 | NLP Learning, Experiments & Analysis

## Overview
This repository contains my learning, experiments, and hands-on work carried out during the **Winter in Data Science (WiDS) 2025–26 program**.

The core notebooks were provided by the program mentors as learning material.  
My contribution includes:
- Executing and understanding all notebooks
- Modifying training parameters and inputs
- Performing task-specific experiments
- Observing and analysing model behavior
- Documenting conceptual and practical learnings

This repository is submitted as part of the **WiDS Endterm Evaluation** and reflects my individual understanding and effort.


## What I Did

### 1. Code Execution & Understanding
- Ran all mentor-provided notebooks end-to-end
- Understood each step of the NLP pipeline:
  - tokenization
  - model initialization
  - training
  - evaluation

---

### 2. Experiments & Modifications

#### Sentiment Analysis (IMDb)
- Observed predictions before fine-tuning
- Fine-tuned BERT on IMDb subsets
- Compared model outputs before vs after training
- Tested custom sentences to understand model behavior

#### Natural Language Inference (SNLI)
- Worked with sentence-pair classification
- Analysed prediction errors before fine-tuning
- Fine-tuned BERT for NLI
- Observed challenges in semantic reasoning tasks

---

### 3. Parameter-Level Changes
- Modified:
  - number of epochs
  - batch size
  - maximum sequence length
- Used smaller subsets to balance compute and learning

---

## Concepts Learned
- Static vs contextual word embeddings
- Self-attention and transformer architecture
- Role of `[CLS]` and `[SEP]` tokens
- Transfer learning and fine-tuning
- Limitations of NLP models despite high accuracy

---

## Tools Used
- Python
- PyTorch
- HuggingFace Transformers
- HuggingFace Datasets
- scikit-learn
- NumPy
