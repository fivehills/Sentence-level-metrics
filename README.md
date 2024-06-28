# Sentence-relevance-and-sentence-surprisal

Use Multilingual LLMs to compute sentence-level metrics

## Overview

This project leverages multilingual Large Language Models (LLMs) to compute two key sentence-level metrics: **surprisal** and **semantic relevance**. These metrics are designed to predict how humans process sentences as a whole, providing insights into reading rates and comprehension across various languages.

## The Sentence-Surprisal Script

The sentence-surprisal script computes sentence-level surprisal for multiple languages. The methods rely on the chain rule and negative log-likelihood derived from word probabilities. Surprisal is a measure of how unexpected a sentence is within a given context, based on the probabilities of its constituent words.

### Features:
- Multilingual support for computing sentence surprisal.
- Utilizes the chain rule and negative log-likelihood from word probability.
- Predicts human reading rates by analyzing sentence-level surprisal.

## The Sentence-Relevance Script

The sentence-relevance script calculates sentence-level semantic relevance for a given sentence within its context in a multilingual setting. Semantic relevance measures how contextually appropriate a sentence is, providing insights into its coherence and meaningfulness.

### Features:
- Computes semantic relevance for sentences in multiple languages.
- Evaluates contextual appropriateness and coherence.
- Predicts human reading rates by analyzing sentence-level semantic relevance.

## Applications

Both sentence-level metrics computed by these scripts can be used to:
- Predict reading rates for various languages.
- Understand human sentence processing.
- Enhance natural language understanding in multilingual contexts.

## Citation

If you use these scripts or metrics in your research, please cite the following paper:

```
@article{sun2024computational,
  title={Computational Sentence-level Metrics Predicting Human Sentence Comprehension},
  author={Sun, Kun and Wang, Rong},
  journal={arXiv preprint arXiv:2403.15822},
  year={2024}
}
```

## Contact

For any questions, suggestions, or feedback, please contact us at [sharpksun@hotmail.com](mailto:sharpksun@hotmail.com).

---

We hope these tools will aid in your research and contribute to the understanding of human sentence processing across languages. Your feedback and contributions are highly valued.

```
