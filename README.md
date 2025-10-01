# Online Inverse Linear Optimization

This repository offers a source code to reproduce the experiments of our paper: "Online Inverse Linear Optimization: Efficient Logarithmic-Regret Algorithm, Robustness to Suboptimality, and Lower Bounds," which is to appear in NeurIPS 2025.

## Overview
We compare three methods:
- **ONS**: our proposed method based on the online Newton step,
- **OGD**: a method based on the online gradient descent by [Bärmann et al. (2020)](https://arxiv.org/abs/1810.12997), and 
- **CP**: a cutting-plane–style heuristic using randomized centroid approximation, inspired by [Gollapudi et al. (2021)](https://proceedings.neurips.cc/paper/2021/hash/bdc6c33585d0cf5d2a8cb83141cd037f-Abstract.html).


## Contents
A notebook to:
- run one trial of OGD / ONS / CP and log **per-round regret** and **runtime**, 
- run **multiple independent trials** and plot **mean ± 1 sd** curves, and
- summarize the final time horizon results (mean & sd).

## Environment
Only standard scientific Python stack is needed:
- `numpy`
- `matplotlib`
