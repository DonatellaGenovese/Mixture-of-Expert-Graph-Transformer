# Mixture of Experts Graph Transformer
Pytorch implementation for the paper [Mixture-of-Experts Graph Transformers for Interpretable Particle Collision Detection](https://arxiv.org/abs/2501.03432). 

<img src="images/teaser.png" alt="Teaser" width="800"/>

## TL;DR
The MoE Graph Transformer achieves competitive accuracy in classifying rare particle collisions while embedding interpretability through attention maps and expert specialization, offering a transparent tool for high-energy physics analysis.

## Data 
The dataset used to train the model is available at [this link](https://github.com/alessiodevoto/sparticles)

## Metrics 
We train and evaluate the model and compare it with other architectures (Multilayer perception, Graph Convolutional Neural network, Graph Transformer). The results are shown in the table \
<img src="images/Metrics.png" alt="Metrics" width="800"/>

## Explainability visualization
<img src="images/expert.png" alt="Attention Maps" width="600"/>
<img src="images/AttentionMaps.png" alt="Attention Maps" width="600"/>

## Cite 

Please cite our work if you found it useful 

@article{genovese2025,
author = {Genovese, Donatella and Sgroi, Alessandro and Devoto, Alessio and Valentine, Samuel and Wood, Lennox and Sebastiani, Cristiano and Scardapane, Simone and D'Onofrio, Monica and Giagu, Stefano},
year = {2025},
month = {07},
pages = {},
title = {Mixture-of-experts graph transformers for interpretable particle collision detection},
volume = {15},
journal = {Scientific Reports},
doi = {10.1038/s41598-025-12003-9}
}
