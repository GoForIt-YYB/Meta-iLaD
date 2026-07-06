# Meta-iLaD: Identifiable Latent Dynamics via Meta-Learning of Dynamics Environments

**ICML 2026**

[Yubo Ye](https://github.com/GoForIt-YYB)¹, Sweekar Piya², Xiajun Jiang², Linwei Wang¹

¹ Rochester Institute of Technology &nbsp;&nbsp; ² Rowan University

[**📄 Paper**](paper.pdf) &nbsp;|&nbsp; [**🖼️ Poster**](poster.pdf)

> **🚧 Code will be released soon. Stay tuned!**

## Abstract

Learning *latent dynamics* is central to assessing the current states and forecasting the future trajectories of high-dimensional time series. For locally-stationary latent dynamics $\mathcal{F}(\mathbf{z}_{<t}; \mathbf{c})$ with latent dynamics state $\mathbf{z}_t$ and environment variable $\mathbf{c}$, prior identifiability results have largely focused on $\mathbf{z}_t$ when conditioned on predefined label $u$ of dynamics environments. This leaves two limitations: reliance on predefined labels that hinder generalization to unseen environments, and a limited understanding of the identifiability of $\mathcal{F}$ and $\mathbf{c}$ which—although offering important structural properties for the identifiability of $\mathbf{z}_t$—are learned jointly with $\mathbf{z}_t$. We address these limitations with **Meta-iLaD**, a novel identifiable latent dynamics framework attained by meta-learning across dynamics environments. Meta-iLaD introduces a novel conditional prior of $\mathbf{c}$, modeled as a feedforward meta-learner to rapidly extract $\mathbf{c}$ from few-shot examples. Meta-iLaD further establishes identifiability for $\mathbf{z}_t$, $\mathbf{c}$, and $\mathcal{F}$ simultaneously, for a general formulation of $\mathcal{F}(\mathbf{z}_{<t}; \mathbf{c})$ without restricting the dimension of $\mathbf{c}$ or how it modulates $\mathcal{F}$. On synthetic and real data, we provide strong empirical evidence that 1) conditioning on few-shot examples enables generalization to out-of-distribution environments, and 2) identifiability for $\mathbf{c}$ and $\mathcal{F}$ is critical for accurate forecasting beyond reconstructing observed trajectories.

## Citation

```bibtex
@inproceedings{ye2026metailad,
  title     = {Meta-iLaD: Identifiable Latent Dynamics via Meta-Learning of Dynamics Environments},
  author    = {Ye, Yubo and Piya, Sweekar and Jiang, Xiajun and Wang, Linwei},
  booktitle = {Proceedings of the 43rd International Conference on Machine Learning (ICML)},
  year      = {2026}
}
```
