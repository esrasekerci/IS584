# IS584: Deep Learning for Text Analytics — Assignments

This repository contains assignment submissions for **IS584: Deep Learning for Text Analytics**, offered at Middle East Technical University (METU), Spring 2025.

---

## Contents

### `assignment_1/`
- **Topic**: Meta-review classification from the ICLR ASAP-Review dataset
- **Tasks**:
  - Custom neural network with `EmbeddingBag`
  - Evaluation with confusion matrix, precision/recall, F1, Cohen’s Kappa
  - Comparison with GloVe-based embeddings
  - Embedding visualization via PCA and t-SNE
  - Error analysis and improved preprocessing (lemmatization + POS)

---

### `assignment_2/`
- **Topic**: Custom BERT-based masked language model for *The Hunger Games*
- **Tasks**:
  - Manual construction of a masked language head (not using `BertForMaskedLM`)
  - Pseudo-perplexity computation
  - Sentence masking, training, and generation
  - Evaluation using validation/test perplexity and masked token predictions
