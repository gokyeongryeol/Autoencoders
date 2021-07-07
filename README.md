# Autoencoders

Pytorch implementation of autoencoders.

Aim to reproduce one or two experimental result(s) of the original papers.

## Dataset

Most experiments are coducted based on MNIST, FreyFace or CelebA datasets which is public for academical use.

## Models (in order of appearance)

* Brief paper summary and discussion items are written as a report inside each directory.

- Denoising Autoencoder [link](https://dl.acm.org/doi/pdf/10.1145/1390156.1390294)
  - corrupting certain portion of the input
- K-sparse Autoencoder [link](https://arxiv.org/pdf/1312.5663.pdf)
  - exploiting only K largest activations as a sparse coding
- Variational Autoencoder [link](https://arxiv.org/pdf/1312.6114.pdf)
  - inferring the latent variable in generative process by autoencoder  
  - applying reparameterization trick for differentiable and non-centered parameterizations
- Stick-Breaking VariationalAutoencoder [link](https://arxiv.org/pdf/1605.06197.pdf)
  - allowing possibly infinite size of latent variable with dirichlet process
- Beta Variational Autoencoer [link](https://openreview.net/pdf?id=Sy2fzU9gl)
  - constraining the value of the regularization term for interpretability
