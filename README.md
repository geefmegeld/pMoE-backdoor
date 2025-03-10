# pMoE-backdoor
Code repository for Master thesis on backdoor attacks on a patch-level Mixture of Expert.

# Model used
- pMoE, https://arxiv.org/pdf/2306.04073, (used implementation from https://github.com/nowazrabbani/pMoE_CNN)

# Data used
- CIFAR-10, https://www.cs.toronto.edu/~kriz/cifar.html
- GTSRB, https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign

# Datasets
In the "Datasets" folder, the datasets can be downloaded there using the links. Furthermore, the hello_kitty.jpg is used for the blend attack and needs to be downloaded too to run the experiments.

# Usage
See the jupyter notebooks in the "folder" tab for the experiments used in our thesis. To run the experiments, the datasets should first be downloaded.

## Requirements
The "requirements.txt" contains all packages with their version of the experiments. Most are redundant packages due to experiments run via Google Colab.
