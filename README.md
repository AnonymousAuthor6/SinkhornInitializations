# Generative Adversarial Learning of Sinkhorn Algorithm Initializations

Welcome to the repository of the paper 'Generative Adversarial Learning of Sinkhorn Algorithm Initializations'.

The paper aims at warm-starting the Sinkhorn algorithm with initializations computed by a neural network, which is trained in an adversarial fashion similar to a GAN using a second, generating neural network.


# Reproduce Results

In order reproduce the results of the paper it is as simple as executing the
`experiment.py` file. The required packages and their versions are detailed in the `requirements.txt` file.
The test data can be generated (scraped from online) by executing the `make_data.py` file.

NB: This package is CUDA compatible 
