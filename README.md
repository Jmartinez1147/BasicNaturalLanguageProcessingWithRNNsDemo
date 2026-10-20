# Basic Natural Language Processing with RNNs Demo

## Dataset

Custom text corpus created from repeated sentences.

## Network

- Character-level language model
- Embedding layer
- GRU layer
- Linear output layer

## Results

Validation Accuracy: 0.9881

Test Accuracy: 0.9881

Predicted Next Character: f

## Training

The model was trained for 10 epochs using:

- CrossEntropyLoss
- Adam optimizer
- Character embeddings
- GRU hidden size of 32

## Controlled Experiment

A smaller GRU hidden size was tested to compare model behavior and complexity.

Reducing hidden size decreases model capacity but may improve efficiency.

## Recommendation

The original GRU configuration produced excellent validation and test performance and would be the preferred prototype.

Future work should explore longer training, larger text corpora, and additional GRU sizes.

## Setup

Install required packages:

```bash
pip install -r requirements.txt
```

Run:

```bash
BasicNaturalLanguageProcessingWithRNNsDemo.ipynb
```

## AI Assistance

Microsoft Copilot was used to assist with notebook organization, code review, troubleshooting, explanations, and README preparation.
