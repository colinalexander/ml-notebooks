# ml-notebooks

A personal study collection of the **68 Understanding Deep Learning exercise notebooks** listed on the book's official website. The notebooks accompany *Understanding Deep Learning* by Simon J. D. Prince (MIT Press, 2023).

- **This repository:** [colinalexander/ml-notebooks](https://github.com/colinalexander/ml-notebooks)
- **Original repository:** [udlbook/udlbook](https://github.com/udlbook/udlbook)
- **Book and notebook index:** [Understanding Deep Learning](https://udlbook.github.io/udlbook/)
- **Downloaded:** October 19, 2026, from upstream commit [`da1334fb8e92`](https://github.com/udlbook/udlbook/commit/da1334fb8e92700e1f2ff3216387da2e68af9d25).

## Contents and provenance

The original exercise notebooks are preserved byte for byte under `Notebooks/ChapXX/`, with their original filenames, author credits, outputs, and Colab badges. Five supporting images, the upstream notebook license, and the upstream directory note are included. Chapter numbering follows the official index, which skips Chapter 14.

These are exercises with intentionally incomplete `TODO` sections. Complete them as you work through the book. The import was checked for completeness, notebook schema validity, and matching upstream file hashes; the exercise code has not been executed.

[sources.json](sources.json) records every notebook's original URL, a brief description, the fixed source commit, its Git blob hash, and its SHA-256 checksum. The inventory contains the 68 notebooks linked in the supplied screenshot and official index.

## Open the notebooks

Browse the catalogue below and open a local notebook with JupyterLab, or use the original **Open in Colab** badge inside it. The badge opens the upstream notebook; save your working copy in your own Colab account.

For a basic local environment, run these commands from the repository directory:

```bash
uv venv .venv
source .venv/bin/activate
uv pip install jupyterlab numpy matplotlib scipy pillow
jupyter lab
```

This installs JupyterLab and the common numerical and plotting packages. Later notebooks also use PyTorch, torchvision, NetworkX, Hugging Face Transformers, or MNIST-1D. Install the packages needed by the notebook you choose; some notebooks contain their own installation or download cells. Datasets and pretrained model weights are downloaded when those cells run. The collection does not define a shared, tested dependency lockfile.

Keep each notebook in its chapter folder so its supporting image paths resolve. Notebooks retain their original Colab-oriented shell commands, including `!wget`; when using the included images locally, skip image download cells if `wget` is unavailable. The source code and its original runtime assumptions are preserved.

## Forking and contributions

You are welcome to fork or copy this collection under the included [MIT notebook license](Notebooks/LICENSE%20%28MIT%29). Preserve the original author credits and license notices in your copies.

This is a personal study collection maintained by the repository owner. External contributions are not accepted: new pull requests are restricted to collaborators, and issues and discussions are disabled.

## Notebook catalogue

Each title links to the local copy. The **Source** link points to the exact upstream version downloaded.

### Chapter 1: Background mathematics

| Notebook | Description | Source |
| --- | --- | --- |
| [1.1 — Background mathematics](Notebooks/Chap01/1_1_BackgroundMathematics.ipynb) | Review the mathematical building blocks used throughout the book, including linear functions, vectors, and matrices. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap01/1_1_BackgroundMathematics.ipynb) |

### Chapter 2: Supervised learning

| Notebook | Description | Source |
| --- | --- | --- |
| [2.1 — Supervised learning](Notebooks/Chap02/2_1_Supervised_Learning.ipynb) | Explore linear regression, adjust its parameters, and visualize the supervised learning loss surface. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap02/2_1_Supervised_Learning.ipynb) |

### Chapter 3: Shallow networks

| Notebook | Description | Source |
| --- | --- | --- |
| [3.1 — Shallow networks I](Notebooks/Chap03/3_1_Shallow_Networks_I.ipynb) | Construct a shallow network with one input and visualize how its hidden units combine into an output function. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap03/3_1_Shallow_Networks_I.ipynb) |
| [3.2 — Shallow networks II](Notebooks/Chap03/3_2_Shallow_Networks_II.ipynb) | Extend shallow networks to two input dimensions and examine their output surfaces and multiple outputs. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap03/3_2_Shallow_Networks_II.ipynb) |
| [3.3 — Shallow network regions](Notebooks/Chap03/3_3_Shallow_Network_Regions.ipynb) | Calculate the maximum number of linear regions produced by shallow networks as input dimension and width change. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap03/3_3_Shallow_Network_Regions.ipynb) |
| [3.4 — Activation functions](Notebooks/Chap03/3_4_Activation_Functions.ipynb) | Compare activation functions and observe how each changes the functions a shallow network can represent. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap03/3_4_Activation_Functions.ipynb) |

### Chapter 4: Deep networks

| Notebook | Description | Source |
| --- | --- | --- |
| [4.1 — Composing networks](Notebooks/Chap04/4_1_Composing_Networks.ipynb) | Feed one neural network into another and visualize how composing networks changes the resulting function. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap04/4_1_Composing_Networks.ipynb) |
| [4.2 — Clipping functions](Notebooks/Chap04/4_2_Clipping_functions.ipynb) | Examine how hidden layers clip and recombine intermediate functions to create more complex outputs. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap04/4_2_Clipping_functions.ipynb) |
| [4.3 — Deep networks](Notebooks/Chap04/4_3_Deep_Networks.ipynb) | Express neural networks with matrices and implement forward propagation through multiple hidden layers. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap04/4_3_Deep_Networks.ipynb) |

### Chapter 5: Loss functions

| Notebook | Description | Source |
| --- | --- | --- |
| [5.1 — Least squares loss](Notebooks/Chap05/5_1_Least_Squares_Loss.ipynb) | Connect least squares regression to Gaussian likelihood and negative log likelihood. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap05/5_1_Least_Squares_Loss.ipynb) |
| [5.2 — Binary cross-entropy loss](Notebooks/Chap05/5_2_Binary_Cross_Entropy_Loss.ipynb) | Derive binary classification probabilities and cross-entropy loss from a Bernoulli likelihood. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap05/5_2_Binary_Cross_Entropy_Loss.ipynb) |
| [5.3 — Multiclass cross-entropy loss](Notebooks/Chap05/5_3_Multiclass_Cross_entropy_Loss.ipynb) | Use softmax outputs and a categorical likelihood to compute multiclass cross-entropy loss. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap05/5_3_Multiclass_Cross_entropy_Loss.ipynb) |

### Chapter 6: Optimization

| Notebook | Description | Source |
| --- | --- | --- |
| [6.1 — Line search](Notebooks/Chap06/6_1_Line_Search.ipynb) | Implement a line search procedure to find the minimum of a one-dimensional function. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap06/6_1_Line_Search.ipynb) |
| [6.2 — Gradient descent](Notebooks/Chap06/6_2_Gradient_Descent.ipynb) | Implement gradient descent and visualize its path across a loss surface. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap06/6_2_Gradient_Descent.ipynb) |
| [6.3 — Stochastic gradient descent](Notebooks/Chap06/6_3_Stochastic_Gradient_Descent.ipynb) | Compare gradient descent with stochastic updates and examine their optimization trajectories. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap06/6_3_Stochastic_Gradient_Descent.ipynb) |
| [6.4 — Momentum](Notebooks/Chap06/6_4_Momentum.ipynb) | Investigate how momentum changes optimization updates and movement across a loss surface. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap06/6_4_Momentum.ipynb) |
| [6.5 — Adam](Notebooks/Chap06/6_5_Adam.ipynb) | Implement Adam and study its adaptive, momentum-based parameter updates. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap06/6_5_Adam.ipynb) |

### Chapter 7: Backpropagation and initialization

| Notebook | Description | Source |
| --- | --- | --- |
| [7.1 — Backpropagation in toy model](Notebooks/Chap07/7_1_Backpropagation_in_Toy_Model.ipynb) | Compute derivatives of a toy composite function to understand the steps behind backpropagation. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap07/7_1_Backpropagation_in_Toy_Model.ipynb) |
| [7.2 — Backpropagation](Notebooks/Chap07/7_2_Backpropagation.ipynb) | Implement forward and backward passes to compute gradients in a deep neural network. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap07/7_2_Backpropagation.ipynb) |
| [7.3 — Initialization](Notebooks/Chap07/7_3_Initialization.ipynb) | Measure how weight initialization affects activation magnitudes and backpropagated gradients. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap07/7_3_Initialization.ipynb) |

### Chapter 8: Performance and generalization

| Notebook | Description | Source |
| --- | --- | --- |
| [8.1 — MNIST-1D performance](Notebooks/Chap08/8_1_MNIST_1D_Performance.ipynb) | Train a simple neural network on MNIST-1D and inspect its classification performance. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap08/8_1_MNIST_1D_Performance.ipynb) |
| [8.2 — Bias-variance trade-off](Notebooks/Chap08/8_2_Bias_Variance_Trade_Off.ipynb) | Separate bias and variance in a toy regression model and explore their trade-off. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap08/8_2_Bias_Variance_Trade_Off.ipynb) |
| [8.3 — Double descent](Notebooks/Chap08/8_3_Double_Descent.ipynb) | Investigate double descent by varying model capacity on MNIST-1D. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap08/8_3_Double_Descent.ipynb) |
| [8.4 — High-dimensional spaces](Notebooks/Chap08/8_4_High_Dimensional_Spaces.ipynb) | Explore geometric and probabilistic properties that behave unexpectedly in high-dimensional spaces. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap08/8_4_High_Dimensional_Spaces.ipynb) |

### Chapter 9: Regularization

| Notebook | Description | Source |
| --- | --- | --- |
| [9.1 — L2 regularization](Notebooks/Chap09/9_1_L2_Regularization.ipynb) | Add an L2 penalty to a Gabor regression model and examine its effect on the fitted solution. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap09/9_1_L2_Regularization.ipynb) |
| [9.2 — Implicit regularization](Notebooks/Chap09/9_2_Implicit_Regularization.ipynb) | Explore the implicit regularization introduced by finite gradient descent step sizes. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap09/9_2_Implicit_Regularization.ipynb) |
| [9.3 — Ensembling](Notebooks/Chap09/9_3_Ensembling.ipynb) | Combine predictions from multiple models and measure how ensembling changes prediction error. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap09/9_3_Ensembling.ipynb) |
| [9.4 — Bayesian approach](Notebooks/Chap09/9_4_Bayesian_Approach.ipynb) | Explore Bayesian model fitting and predictions that account for parameter uncertainty. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap09/9_4_Bayesian_Approach.ipynb) |
| [9.5 — Augmentation](Notebooks/Chap09/9_5_Augmentation.ipynb) | Apply data augmentation to MNIST-1D and investigate its effect on generalization. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap09/9_5_Augmentation.ipynb) |

### Chapter 10: Convolutional networks

| Notebook | Description | Source |
| --- | --- | --- |
| [10.1 — 1D convolution](Notebooks/Chap10/10_1_1D_Convolution.ipynb) | Implement one-dimensional convolution and inspect how convolutional layers transform signals. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap10/10_1_1D_Convolution.ipynb) |
| [10.2 — Convolution for MNIST-1D](Notebooks/Chap10/10_2_Convolution_for_MNIST_1D.ipynb) | Build and evaluate a one-dimensional convolutional classifier for MNIST-1D. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap10/10_2_Convolution_for_MNIST_1D.ipynb) |
| [10.3 — 2D convolution](Notebooks/Chap10/10_3_2D_Convolution.ipynb) | Hand-code two-dimensional convolution and compare the operation with PyTorch. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap10/10_3_2D_Convolution.ipynb) |
| [10.4 — Downsampling & upsampling](Notebooks/Chap10/10_4_Downsampling_and_Upsampling.ipynb) | Explore methods for reducing and increasing the spatial resolution of feature maps. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap10/10_4_Downsampling_and_Upsampling.ipynb) |
| [10.5 — Convolution for MNIST](Notebooks/Chap10/10_5_Convolution_For_MNIST.ipynb) | Train a PyTorch convolutional network to classify handwritten digits in MNIST images. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap10/10_5_Convolution_For_MNIST.ipynb) |

### Chapter 11: Residual networks

| Notebook | Description | Source |
| --- | --- | --- |
| [11.1 — Shattered gradients](Notebooks/Chap11/11_1_Shattered_Gradients.ipynb) | Study how gradients change and lose correlation as neural networks become deeper. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap11/11_1_Shattered_Gradients.ipynb) |
| [11.2 — Residual networks](Notebooks/Chap11/11_2_Residual_Networks.ipynb) | Add residual connections to MNIST-1D networks and investigate their behavior. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap11/11_2_Residual_Networks.ipynb) |
| [11.3 — Batch normalization](Notebooks/Chap11/11_3_Batch_Normalization.ipynb) | Investigate batch normalization within residual networks. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap11/11_3_Batch_Normalization.ipynb) |

### Chapter 12: Transformers

| Notebook | Description | Source |
| --- | --- | --- |
| [12.1 — Self-attention](Notebooks/Chap12/12_1_Self_Attention.ipynb) | Build a self-attention mechanism from scratch using queries, keys, values, and attention weights. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap12/12_1_Self_Attention.ipynb) |
| [12.2 — Multi-head self-attention](Notebooks/Chap12/12_2_Multihead_Self_Attention.ipynb) | Construct multi-head self-attention and combine the results of multiple attention heads. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap12/12_2_Multihead_Self_Attention.ipynb) |
| [12.3 — Tokenization](Notebooks/Chap12/12_3_Tokenization.ipynb) | Build tokens from text and investigate the tokenization process used by language models. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap12/12_3_Tokenization.ipynb) |
| [12.4 — Decoding strategies](Notebooks/Chap12/12_4_Decoding_Strategies.ipynb) | Generate text with GPT-2 using sampling, greedy selection, top-k sampling, nucleus sampling, and beam search. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap12/12_4_Decoding_Strategies.ipynb) |

### Chapter 13: Graph neural networks

| Notebook | Description | Source |
| --- | --- | --- |
| [13.1 — Encoding graphs](Notebooks/Chap13/13_1_Graph_Representation.ipynb) | Represent graph connectivity and node information with matrices. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap13/13_1_Graph_Representation.ipynb) |
| [13.2 — Graph classification](Notebooks/Chap13/13_2_Graph_Classification.ipynb) | Build a graph network that maps molecular structures of different sizes to a binary output. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap13/13_2_Graph_Classification.ipynb) |
| [13.3 — Neighborhood sampling](Notebooks/Chap13/13_3_Neighborhood_Sampling.ipynb) | Explore neighborhood sampling as a way to process graphs without aggregating every neighbor. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap13/13_3_Neighborhood_Sampling.ipynb) |
| [13.4 — Graph attention](Notebooks/Chap13/13_4_Graph_Attention_Networks.ipynb) | Implement graph attention from scratch to weight messages from neighboring nodes. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap13/13_4_Graph_Attention_Networks.ipynb) |

### Chapter 15: Generative adversarial networks

| Notebook | Description | Source |
| --- | --- | --- |
| [15.1 — GAN toy example](Notebooks/Chap15/15_1_GAN_Toy_Example.ipynb) | Explore a toy generative adversarial network and the interaction between its generator and discriminator. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap15/15_1_GAN_Toy_Example.ipynb) |
| [15.2 — Wasserstein distance](Notebooks/Chap15/15_2_Wasserstein_Distance.ipynb) | Compute Wasserstein distance through an optimal transport linear program and compare distribution divergences. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap15/15_2_Wasserstein_Distance.ipynb) |

### Chapter 16: Normalizing flows

| Notebook | Description | Source |
| --- | --- | --- |
| [16.1 — 1D normalizing flows](Notebooks/Chap16/16_1_1D_Normalizing_Flows.ipynb) | Transform one-dimensional probability distributions with invertible normalizing flows. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap16/16_1_1D_Normalizing_Flows.ipynb) |
| [16.2 — Autoregressive flows](Notebooks/Chap16/16_2_Autoregressive_Flows.ipynb) | Implement an autoregressive flow, its inverse, and a check that the transformation is invertible. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap16/16_2_Autoregressive_Flows.ipynb) |
| [16.3 — Contraction mappings](Notebooks/Chap16/16_3_Contraction_Mappings.ipynb) | Use fixed-point iteration with contraction mappings and invert a residual transformation. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap16/16_3_Contraction_Mappings.ipynb) |

### Chapter 17: Latent variable models

| Notebook | Description | Source |
| --- | --- | --- |
| [17.1 — Latent variable models](Notebooks/Chap17/17_1_Latent_Variable_Models.ipynb) | Explore a nonlinear latent variable model and how hidden variables generate observed data. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap17/17_1_Latent_Variable_Models.ipynb) |
| [17.2 — Reparameterization trick](Notebooks/Chap17/17_2_Reparameterization_Trick.ipynb) | Investigate the reparameterization trick for computing gradients through random samples. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap17/17_2_Reparameterization_Trick.ipynb) |
| [17.3 — Importance sampling](Notebooks/Chap17/17_3_Importance_Sampling.ipynb) | Estimate quantities using importance sampling and examine the role of proposal distributions. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap17/17_3_Importance_Sampling.ipynb) |

### Chapter 18: Diffusion models

| Notebook | Description | Source |
| --- | --- | --- |
| [18.1 — Diffusion encoder](Notebooks/Chap18/18_1_Diffusion_Encoder.ipynb) | Implement a diffusion encoder and visualize the gradual corruption of data with noise. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap18/18_1_Diffusion_Encoder.ipynb) |
| [18.2 — 1D diffusion model](Notebooks/Chap18/18_2_1D_Diffusion_Model.ipynb) | Build a one-dimensional diffusion model and sample data through its learned reverse process. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap18/18_2_1D_Diffusion_Model.ipynb) |
| [18.3 — Reparameterized model](Notebooks/Chap18/18_3_Reparameterized_Model.ipynb) | Reparameterize a diffusion model to predict noise and generate samples through reverse diffusion. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap18/18_3_Reparameterized_Model.ipynb) |
| [18.4 — Families of diffusion models](Notebooks/Chap18/18_4_Families_of_Diffusion_Models.ipynb) | Explore families of diffusion sampling processes inspired by denoising diffusion implicit models. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap18/18_4_Families_of_Diffusion_Models.ipynb) |

### Chapter 19: Reinforcement learning

| Notebook | Description | Source |
| --- | --- | --- |
| [19.1 — Markov decision processes](Notebooks/Chap19/19_1_Markov_Decision_Processes.ipynb) | Simulate Markov processes, rewards, actions, and discounted returns in a gridworld. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap19/19_1_Markov_Decision_Processes.ipynb) |
| [19.2 — Dynamic programming](Notebooks/Chap19/19_2_Dynamic_Programming.ipynb) | Use dynamic programming for tabular reinforcement learning in a gridworld. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap19/19_2_Dynamic_Programming.ipynb) |
| [19.3 — Monte-Carlo methods](Notebooks/Chap19/19_3_Monte_Carlo_Methods.ipynb) | Estimate values and improve a tabular reinforcement learning policy using Monte Carlo episodes. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap19/19_3_Monte_Carlo_Methods.ipynb) |
| [19.4 — Temporal difference methods](Notebooks/Chap19/19_4_Temporal_Difference_Methods.ipynb) | Apply temporal difference methods to learn from transitions in the penguin gridworld. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap19/19_4_Temporal_Difference_Methods.ipynb) |
| [19.5 — Control variates](Notebooks/Chap19/19_5_Control_Variates.ipynb) | Use correlated control variates to reduce the variance of Monte Carlo estimates. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap19/19_5_Control_Variates.ipynb) |

### Chapter 20: Understanding deep learning behavior

| Notebook | Description | Source |
| --- | --- | --- |
| [20.1 — Random data](Notebooks/Chap20/20_1_Random_Data.ipynb) | Investigate neural network training on random data and its implications for memorization. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap20/20_1_Random_Data.ipynb) |
| [20.2 — Full-batch gradient descent](Notebooks/Chap20/20_2_Full_Batch_Gradient_Descent.ipynb) | Train a network with full-batch gradient descent and examine its learning behavior. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap20/20_2_Full_Batch_Gradient_Descent.ipynb) |
| [20.3 — Lottery tickets](Notebooks/Chap20/20_3_Lottery_Tickets.ipynb) | Prune and retrain neural networks to investigate sparse subnetworks and the lottery ticket phenomenon. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap20/20_3_Lottery_Tickets.ipynb) |
| [20.4 — Adversarial attacks](Notebooks/Chap20/20_4_Adversarial_Attacks.ipynb) | Construct fast gradient sign adversarial examples against an MNIST convolutional classifier. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap20/20_4_Adversarial_Attacks.ipynb) |

### Chapter 21: Bias and explainability

| Notebook | Description | Source |
| --- | --- | --- |
| [21.1 — Bias mitigation](Notebooks/Chap21/21_1_Bias_Mitigation.ipynb) | Explore post-processing methods for mitigating bias in a simulated loan decision system. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap21/21_1_Bias_Mitigation.ipynb) |
| [21.2 — Explainability](Notebooks/Chap21/21_2_Explainability.ipynb) | Use LIME-style local explanations to interpret a simulated black-box credit scoring model. | [Upstream](https://github.com/udlbook/udlbook/blob/da1334fb8e92700e1f2ff3216387da2e68af9d25/Notebooks/Chap21/21_2_Explainability.ipynb) |

## Attribution and license

The notebooks are by Simon Prince, with additional contributors credited in the original files. They are redistributed under the upstream [MIT notebook license](Notebooks/LICENSE%20%28MIT%29), copyright 2023 Simon Prince. That license and the original author notices are preserved. The source book and other materials in the upstream repository have their own terms; this collection contains the exercise notebooks and their supporting files.
