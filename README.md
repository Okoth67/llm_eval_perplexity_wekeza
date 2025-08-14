# LLM Evaluation Practice — Perplexity Metric

## Overview
This repository is part of my ongoing practice in **LLM evaluation**.  
In this notebook, I focus on **perplexity**, one of the most fundamental metrics for evaluating the fluency and predictive capability of language models.

Perplexity measures how well a model predicts a sequence of tokens, lower values indicate more confident and accurate predictions. In this experiment, I use my fine-tuned **Wekeza GPT-2** model to compute perplexity scores for short finance-related texts.

## Reference Paper
- Jelinek, F., Mercer, R. L., Bahl, L. R., & Baker, J. K. (1977). *Perplexity—a measure of the difficulty of speech recognition tasks*. IEEE Transactions on Acoustics, Speech, and Signal Processing.
- Additional relevant reading: *A Neural Probabilistic Language Model* — Bengio et al. (2003).

## What’s in the Notebook
- Load a fine-tuned Wekeza GPT-2 model
- Tokenize and prepare evaluation data
- Compute and display perplexity for each sentence
- Interpret the results in terms of model fluency
