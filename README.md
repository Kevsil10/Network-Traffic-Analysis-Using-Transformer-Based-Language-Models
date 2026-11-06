# Network Traffic Analysis Using Transformer-Based Language Models

**Master's Thesis Project | Big Data · Machine Learning · Deep Learning · Telecommunications**

## Overview

This repository documents a research project developed as part of a Master's thesis in Big Data.

The project explores the application of transformer-based language models to network traffic classification, examining their potential use in telecommunications and network security analysis.

Three models are considered in the original research:

- **BERT** — Bidirectional Encoder Representations from Transformers
- **RoBERTa** — Robustly Optimized BERT Pretraining Approach
- **GPT-2** — Generative Pre-trained Transformer 2

The repository is being organized as a technical portfolio documenting the experiments, methodology, and results of the original research.

## Project Objectives

- Explore the use of transformer architectures for network traffic classification.
- Prepare and process network traffic datasets using Python.
- Apply pretrained language models to classification tasks.
- Evaluate experimental results using established classification metrics.
- Investigate potential applications in telecommunications and network security.

## Dataset

The published BERT experiment uses **UNSW-NB15**, a network intrusion detection dataset containing normal and malicious traffic.

The experiment transforms selected categorical network features into textual representations for processing by BERT.

**Scope clarification:** UNSW-NB15 is not a native 5G traffic dataset. The project investigates methods relevant to network traffic analysis, with potential applications to future telecommunications environments.

## Published Experiments

| Model | Description | Status |
|---|---|---|
| BERT | Binary network traffic classification | Notebook published |
| RoBERTa | Transformer-based classification experiment | Documentation pending |
| GPT-2 | Language-model-based experiment | Documentation pending |

### BERT Experiment

[View BERT Experiment Notebook](notebook/bert_experiment.ipynb)

The notebook documents:

- Dataset loading and preprocessing.
- Conversion of selected network features into textual input.
- Balanced training sample selection.
- BERT tokenization and fine-tuning.
- Binary classification of normal and attack traffic.
- Evaluation using classification metrics and confusion matrices.

The notebook contains saved experimental outputs. These represent the recorded research results and have not yet been independently reproduced in a new environment.

## Technologies

- Python
- Pandas and NumPy
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab
- Git and GitHub

## Repository Structure

```text
llm-5g-network-traffic-analysis/
├── README.md
├── notebook/
│   └── bert_experiment.ipynb
└── docs/
```

Additional research artifacts and documentation will be incorporated progressively.

## Research Context

This project originates from a Master's thesis investigating transformer-based language models for network traffic analysis.

The current publication focuses on documenting the work completed during the research. Further code refactoring, reproducibility improvements, and experimental validation are planned as subsequent development activities.

## Author

**Kevin Silva Castro**

Telematics Engineer | Master's in Big Data | Cloud Computing | Telecommunications

**Professional interests:** Data Analytics, Machine Learning, AI Engineering, Network Analytics and Cloud Technologies.
