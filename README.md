# karpathy

A walk through of [Andrej Karpathy's](https://karpathy.ai/) video series [Neural Networks: Zero to Hero](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) along with supplemental material and deep-dives.

[Zero to Hero on Discord](https://discord.gg/3zy8kqD9Cp)

## [The spelled-out intro to neural networks and backpropagation: building micrograd](https://youtu.be/VMj-3S1tku0)

A tiny scalar-valued autograd engine and a neural net library on top of it with PyTorch-like API.

[GitHub Repository](https://github.com/karpathy/micrograd)

## Makemore

An autoregressive character-level language model for making more things.

[GitHub Repository](https://github.com/karpathy/makemore)

### [The spelled-out intro to language modeling: building makemore](https://youtu.be/PaCmpygFfXo)

We implement a bigram character-level language model, which we will further complexify in followup videos into a modern Transformer language model, like GPT. In this video, the focus is on (1) introducing torch.Tensor and its subtleties and use in efficiently evaluating neural networks and (2) the overall framework of language modeling that includes model training, sampling, and the evaluation of a loss (e.g. the negative log likelihood for classification).

Supplemental material:

- [Python + Numpy tutorial from CS231n](https://cs231n.github.io/python-numpy-tutorial/)
- [PyTorch tensors tutorial](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html)
- [Introduction to Torch’s tensor library](https://pytorch.org/tutorials/beginner/nlp/pytorch_tutorial.html)

## [Let's build GPT: from scratch, in code, spelled out.](https://youtu.be/kCc8FmEb1nY)

Supplemental material:

- [Explainable AI: Visualizing Attention in Transformers](https://generativeai.pub/explainable-ai-visualizing-attention-in-transformers-4eb931a2c0f8)
