# Multi-granularity episodic contrastive learning for few-shot learning [PR 2022]
Official PyTorch implementation of [Multi-granularity episodic contrastive learning for few-shot learning](https://www.sciencedirect.com/science/article/pii/S0031320322003016)
## Running the code
### Preliminaries  
**Datasets**  

miniImageNet (courtesy of Spyros Gidaris)  
tieredImageNet (courtesy of Kwonjoon Lee)  
FC100  
Download the datasets and link the folders into materials/ with names mini-imagenet, tiered-imagenet and FC100.

In following we take FC100 as an example. By default it is 1-shot, modify shot in config file for other shots. Models are saved in save/.

### 1. Transfer learning baseline
python train_classifier.py --config configs/train_classifier_FC100.yaml --gpu 0
### 2. Multi-granularity episodic contrastive learning

## Citation
> @article{ZHU2022108820,  
author = {Pengfei Zhu and Zhilin Zhu and Yu Wang and Jinglin Zhang and Shuai Zhao},  
title = {Multi-granularity episodic contrastive learning for few-shot learning},  
journal = {Pattern Recognition},  
volume = {131},  
pages = {108820},  
year = {2022},  
issn = {0031-3203},  
doi = {https://doi.org/10.1016/j.patcog.2022.108820}}  
  	
  	
  	
  	
  	
  	
  	
