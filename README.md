# Mixture of Experts Graph Transformer
Pytorch implementation for the paper [Mixture-of-Experts Graph Transformers for Interpretable Particle Collision Detection](https://arxiv.org/abs/2501.03432). 

<img src="images/teaser.png" alt="Teaser" width="800"/>

## TL;DR
The MoE Graph Transformer achieves competitive accuracy in classifying rare particle collisions while embedding interpretability through attention maps and expert specialization, offering a transparent tool for high-energy physics analysis.

## Data 
The dataset used to train the model is available at [this link](https://github.com/alessiodevoto/sparticles)

## Metrics 
We train and evaluate the model and compare it with other architectures (Multilayer perception, Graph Convolutional Neural network, Graph Transformer). The results are shown in the table \
<img src="images/metrics.png" alt="Metrics" width="800"/>

## Explainability visualization
<img src="images/expert.png" alt="Attention Maps" width="600"/>
<img src="images/AttentionMaps.png" alt="Attention Maps" width="600"/>

## Cite 
Please cite our work if you found it useful
@article{genovese2025mixtureofexpertsgraphtransformersinterpretable,
  title     = {Mixture-of-Experts Graph Transformers for Interpretable Particle Collision Detection},
  author    = {Donatella Genovese and Alessandro Sgroi and Alessio Devoto and Samuel Valentine and Lennox Wood and Cristiano Sebastiani and Stefano Giagu and Monica D'Onofrio and Simone Scardapane},
  journal   = {Scientific Reports},
  year      = {2025},
  volume    = {15},
  number    = {},
  pages     = {12003},
  doi       = {10.1038/s41598-025-12003-9},
  url       = {https://www.nature.com/articles/s41598-025-12003-9}
}
