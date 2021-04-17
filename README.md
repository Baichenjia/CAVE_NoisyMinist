# Conditional VAE for Exploration in Noisy Mnist (Baseline of VDM)

## Prerequisites

tensorflow-gpu 1.13.1 or 1.14.0,
tensorflow-probability 0.6.0,
openAI [baselines](https://github.com/openai/baselines),


## run for Noisy Mnist

The following command should train the Probabilistic Ensemble for "noise mnist" MDP.

```
python noise_mnist.py
```

This command will train for 200 epochs. The weights are saved in `model/`. Then use following command to perform the conditional generation process to produce the figures.
```
python noise_mnist_test.py
```
