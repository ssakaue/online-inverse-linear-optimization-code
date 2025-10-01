# Online Inverse Linear Optimization

This repository contains a source code to reproduce the experiments from the paper: "Online Inverse Linear Optimization: Efficient Logarithmic-Regret Algorithm, Robustness to Suboptimality, and Lower Bounds" by Shinsaku Sakaue, Taira Tsuchiya, Han Bao, and Taihei Oki.

## Overview
We compare three methods:
- **ONS**: our proposed method based on the online Newton step,
- **OGD**: a method based on the online gradient descent by Bärmann et al. (2020), and 
- **CP**: A cutting-plane–style heuristic using randomized centroid approximation, inspired by Gollapudi et al. (2021).


## What’s Included
A notebook to:
- run one trial of OGD / ONS / CP and log **per-round regret** and **runtime**, 
- run **multiple independent trials** and plot **mean ± 1 sd** curves, and
- summarize the final horizon \(T\) results (mean & sd).

## Environment
Only standard scientific Python stack is needed:
- `numpy`
- `matplotlib`
