# SEDEM

# Self-Evolved Dynamic Expansion Model for Task-Free Continual Learning

>📋 This is the implementation of Self-Evolved Dynamic Expansion Model for Task-Free Continual Learning

>📋 Accepted by ICCV 2023

# Title : Self-Evolved Dynamic Expansion Model for Task-Free Continual Learning

# Paper link : 



# Abstract

Task-Free Continual Learning (TFCL) aims to learn new concepts from a stream of data without any task information. The Dynamic Expansion Model (DEM) has shown promising results in TFCL by dynamically expanding the model's capacity to deal with shifts in the data distribution. However, existing approaches only consider the recognition of the input shift as the expansion signal and ignore the correlation between previously learned knowledge and the new incoming data, resulting in adding and training unnecessary parameters. In this paper, we propose a novel and effective framework for TFCL, which dynamically expands the architecture of a DEM model through a self-assessment mechanism evaluating the diversity of knowledge among experts as expansion signals. This mechanism ensures learning additional underlying data distributions with a compact model structure. Moreover, a novelty-aware sample selection approach is proposed to manage the memory buffer that forces the newly added expert to learn novel information from a data stream, which further promotes the diversity among experts. Since knowledge transfer in TFCL is less explored, we also propose to reuse previously learned representation information for learning new incoming data. The DEM expansion and training are regularised  through a gradient updating mechanism to gradually explore the positive forward transfer, further improving the performance. The empirical results on TFCL benchmarks show that the proposed framework outperforms the state-of-the-art while only employing a reasonable number of parameters.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:





 
