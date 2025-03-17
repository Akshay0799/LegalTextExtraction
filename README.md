# Automated Extraction of Regulations from Legal Texts

This repo contains two notebooks for extracting Legal regulations using BiLSTM and simple Keyword-based methods respectively.
To address the issue of human errors and save time in the process of reading through the legal guidelines, we propose the use of Natural Language
Processing(NLP) to extract important requirements from the legal regulations, focusing solely on the Food and Packaging Industry. The proposed NLP pipeline will utilize BiLSTM neural networks trained on annotated regulatory texts obtained from the Canadian Regulations to build multiple binary classifiers for each class of requirement. Keyword-based mechanisms using heuristic functions that would serve as a baseline system for the proposed approach have also been introduced.

### Technologies

* Python
* PyTorch
* Sci-kit Learn
* NLTK
* Optuna


### Algorithms

* BiLSTM
* Bayesian Optimization for Hyper Parameter Tuning
* Heuristic-based approaches to extract keywords

