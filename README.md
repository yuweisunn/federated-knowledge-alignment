## This is a PyTorch implementation of the paper [Feature Distribution Matching for Federated Domain Generalization (ACML 2022)](https://arxiv.org/abs/2203.11635).

## Table of Contents
* [General information](#general-information)
* [Running the systems](#running-the-systems)
* [Further readings](#further-readings)

## General information
FedKA that consists of three building blocks, i.e., features disentangler, embedding matching, and federated voting, aims to improve the global model’s generality in tackling an unseen task with knowledge transferred from different clients’ model learning.

<p align="center">
<img src="fedka.png" width="80%"/>
</p>

## Running the systems
The systems in the Digit-Five tasks can be run with the Jupyter Notebook "FedKA-Digit-Five.ipynb".
The dataset can be downloaded from [Digit-Five.](https://drive.google.com/drive/folders/1nwa-9TPm_-pZsE9uNalaDS909LXNaFjT?usp=sharing)

## Citation
If this repository is helpful for your research or you want to refer the provided results in this work, you could cite the work using the following BibTeX entry:

```
@article{sun2022fedka,  
  author = {Sun, Yuwei and Chong, Ng and Hideya, Ochiai},
  title = {Feature Distribution Matching for Federated Domain Generalization},
  journal = {ACML},
  year = {2022}
}
```

## Further readings
* [Decentralized Deep Learning for Multi-Access Edge Computing: A Survey on Communication Efficiency and Trustworthiness](https://www.techrxiv.org/articles/preprint/Decentralized_Deep_Learning_for_Multi-Access_Edge_Computing_A_Survey_on_Communication_Efficiency_and_Trustworthiness/16691230), Yuwei Sun et al., IEEE Transactions on Artificial Intelligence.  
