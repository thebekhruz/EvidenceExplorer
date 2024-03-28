# Natural Language Inference (NLI) Classifier

This project aims to develop a Natural Language Inference (NLI) system from scratch, capable of determining whether a given hypothesis is true based on a provided premise. The NLI model leverages over 26K premise-hypothesis pairs for training and more than 6K pairs for validation to understand and infer the relationship between premise and hypothesis statements.

## Overview

Natural Language Inference, a key task in natural language understanding (NLU), involves evaluating if a hypothesis is true (entailment), false (contradiction), or undetermined (neutral) based on a given premise. This project focuses on accurately classifying the relationship between pairs of sentences into these categories.

## Dataset

- **Training Data**: Over 26,000 premise-hypothesis pairs.
- **Validation Data**: More than 6,000 pairs.
- The dataset is designed to challenge the model's understanding of semantics, logic, and real-world knowledge.

## Getting Started

### Prerequisites

- Python 3.8 or later
- Pip for Python package installation

### Installation

1. Clone the repository:
```bash
    git clone git@github.com:thebekhruz/PairwiseSeqClassify.git
```

2. Install the required Python packages:
``` bash
    pip install -r requirements.txt
```

### Training the Model
To train the NLI model, run:
```
python train.py
```

