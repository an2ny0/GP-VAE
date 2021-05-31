# GP-VAE: Deep Probabilistic Multivariate Time Series Imputation

The paper based on: http://proceedings.mlr.press/v108/fortuin20a/fortuin20a.pdf

Proposal: research the model from the paper and implement it in finance.

Project goals:

1. Realise the model:
- Use deep variational autoencoders (VAEs) to map the missing data time series into a latent space without missingness;
- Model the low-dimensional dynamics with a Gaussian process (GP). 
2. Try the model on physionet data.
3. Check the results of the model with paper based on.
4. Implement the model with historical values of prices and weights of Moscow Exchange (MOEX).
