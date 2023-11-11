## Quantile Importance Sampling 

**Preprint**: [https://arxiv.org/abs/2305.03158](https://arxiv.org/abs/2305.03158)

**Authors**: Jyotishka Datta, and Nicholas G. Polson. 


### Abstract 

In Bayesian inference, the approximation of integrals of the form $\psi = \mathbb{E}_{F}{l(X)} = \int_{\chi} l(\mathbf{x}) dF(\mathbf{x})$ is a fundamental challenge. Such integrals are crucial for evidence estimation, which is important for various purposes, including model selection and numerical analysis. The existing strategies for evidence estimation are classified into four categories: deterministic approximation, density estimation, importance sampling, and vertical representation (Llorente et al. ,2020). In this paper, we show that the Riemann sum estimator due to Yakowitz (1978) can be used in the context of nested sampling (Skilling, 2006) to achieve a $O(n^{-4})$ rate of convergence, faster than the usual Ergodic Central Limit Theorem, under certain regularity conditions. We provide a brief overview of the literature on the Riemann sum estimators and the nested sampling algorithm and its connections to vertical likelihood Monte Carlo. We provide theoretical and numerical arguments to show how merging these two ideas may result in improved and more robust estimators for evidence estimation, especially in higher dimensional spaces. We also briefly discuss the idea of simulating the Lorenz curve that avoids the problem of intractable $\Lambda$ functions, essential for the vertical representation and nested sampling. 

## Examples 

We show a couple of examples to demonstrate the efficiency of QIS vs. other common strategies. The individual quarto markdown files and the rendered html files are available in the repository as QIS.qmd, QIS.html and QIS_MVT.qmd, QIS_MVT.html respectively. 

1. Normal prior, normal likelihood: https://htmlpreview.github.io/?https://github.com/DattaHub/QIS/blob/main/QIS.html
2. Multivariate t-likelihood: https://htmlpreview.github.io/?https://github.com/DattaHub/QIS/blob/main/QIS_MVT.html




