# Alternative Models for Direct Policy Search in Reinforcement Learning Control Problems

## Overview
Welcome to the repository for the report of the master thesis project titled "Alternative Models for Direct Policy Search in Reinforcement Learning Control Problems". The research was conducted in collaboration with the eXascale Infolab in Fribourg.

### Repository Contents
- **Thesis Report:** The report detailing the research, methodologies, and findings of this project is available as `main.pdf`.
- **Supplementary Materials:** Additional documents and resources utilized during the making of the report are included in this repository for reference and further exploration.

### Template Credits
The structure and format of this repository were taken from the eXascale Infolab thesis template. For more details on the template or how to use it for your project, visit [eXascale Infolab Thesis Template](https://github.com/eXascaleInfolab/thesis_template).

### Getting Started
To dive into the thesis:
1. **Download the Thesis:** Click on `main.pdf` to download the full report.
2. **Explore Additional Resources:** Browse through the supplementary materials.

## Abstract
Neural networks as generic function approximators can solve many challenging problems. Regardless, they can only be applied successfully for a suited problem structure. A large part of the success of neural networks can be attributed to the efficiency of the backpropagation algorithm, which requires labeled data to estimate accurate error gradients. However, there are many areas where accessing labeled data is non-trivial, including problems in reinforcement learning. In contrast, black-box optimization techniques are less limiting and can be used to optimize the parameters of any function approximator. They presume no constraints on the problem structure, the model, or the solution. With this flexibility, we can study alternative models to neural networks that are yet unexplored in the context of reinforcement learning.
This thesis aims to achieve comparable results with a function approximator other than neural networks. To this end, I analyzed the performance of polynomial and binary tree models on reinforcement learning benchmark problems. I compared these results to those of neural networks. The results show that the binary tree model can produce results comparable to neural networks, and even outperforms them, while providing essential advantages. The simple structure of the binary tree model makes hyperparameter tuning straightforward and provides high interpretability.
