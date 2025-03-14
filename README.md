# LASER

official code of Long-term Causal Effects Estimation via Latent Surrogates Representation Learning [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0893608024002600)

# Cite this paper

```
@article{CAI2024106336,
title = {Long-term causal effects estimation via latent surrogates representation learning},
journal = {Neural Networks},
volume = {176},
pages = {106336},
year = {2024},
issn = {0893-6080},
doi = {https://doi.org/10.1016/j.neunet.2024.106336},
url = {https://www.sciencedirect.com/science/article/pii/S0893608024002600},
author = {Ruichu Cai and Weilin Chen and Zeqin Yang and Shu Wan and Chen Zheng and Xiaoqing Yang and Jiecheng Guo},
keywords = {Long-term causal effects, Surrogates, LASER, Identifiable variational autoencoder},
abstract = {Estimating long-term causal effects based on short-term surrogates is a significant but challenging problem in many real-world applications such as marketing and medicine. Most existing methods estimate causal effects in an idealistic and simplistic manner — disregarding unobserved surrogates and treating all short-term outcomes as surrogates. However, such methods are not well-suited to real-world scenarios where the partially observed surrogates are mixed with the proxies of unobserved surrogates among short-term outcomes. To address this issue, we develop our flexible method called LASER to estimate long-term causal effects in a more realistic situation where the surrogates are either observed or have observed proxies. In LASER, we employ an identifiable variational autoencoder to learn the latent surrogate representation by using all the surrogate candidates without the need to distinguish observed surrogates or proxies of unobserved surrogates. With the learned representation, we further devise a theoretically guaranteed and unbiased estimation of long-term causal effects. Extensive experimental results on the real-world and semi-synthetic datasets demonstrate the effectiveness of our proposed method.}
}
```
