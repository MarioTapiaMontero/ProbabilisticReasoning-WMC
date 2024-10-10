# Probabilistic Reasoning via Weighted Model Counting
---

## Description
The project involved probabilistic reasoning using weighted model counting on Bayesian networks. Two classical datasets, the Sprinkler and Asia datasets, were utilized to represent uncertain knowledge in graphical models. The solver Minisat22, from PySAT, was employed to compute weighted model counts, allowing the evaluation of probabilities across different scenarios. The goal was to efficiently reason about the likelihood of various events (probability of a query given an evidence), leveraging the structure of Bayesian networks to handle complex probabilistic queries.

## Keywords
Bayesian Networks, Weighted Model Counting, Probabilistic Reasoning

## Data
Two datasets from the BNLearn package were used:
- Sprinkler: The dataset consists of 1,000 instances with four binary variables: Cloudy, Sprinkler, Rain, and Wet Grass. In this network, the variable Cloudy influences both Sprinkler and Rain. Sprinkler and Rain, in turn, determine the state of Wet Grass.
- Asia: The dataset consists of 10,000 instances with eight binary variables: Dyspnoea, Tuberculosis, Lung Cancer, Bronchitis, Visit to Asia, Smoking, Chest X-ray, and Tuberculosis versus Lung Cancer/Bronchitis. It represents a Bayesian network that models the relationships between lung diseases and risk factors. The variables capture interactions between visiting Asia, smoking habits, and the likelihood of developing conditions like tuberculosis, lung cancer, or bronchitis, as well as how these factors influence symptoms like dyspnoea and test results such as chest X-rays.



## Methods
- Heuristic followed from Sang et al. 2005

## Software
Python

## Files
* Code:
  

---
