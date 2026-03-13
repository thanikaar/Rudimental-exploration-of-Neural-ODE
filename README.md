# Rudimental-exploration-of-Neural-ODE

## 1. Introduction

This repository contains the coursework and experiments developed for **UGST4090 – Introduction to Optimization**.

The project provides a rudimentary exploration of **Neural Ordinary Differential Equations (Neural ODEs)**, a class of deep learning models that parameterize the derivative of a hidden state using a neural network, rather than specifying discrete layer-by-layer transformations. This allows continuous-depth models and opens up a range of applications in time-series modelling, generative modelling, and beyond.

The repository is organized across multiple branches, each targeting a distinct experimental focus — from a clean implementation of the Neural ODE solver, to comparisons against standard baselines on image classification and time-series forecasting tasks.

---

## 2. Repository Structure

```
Rudimental-exploration-of-Neural-ODE/
├─ README.md
├─ .gitignore
├─ .gitattributes
├─ data/
│  └─ .gitkeep
├─ notebooks/
│  └─ .gitkeep
├─ src/
│  └─ __init__.py
```

### Branches

| Branch | Description |
|---|---|
| `main` | Stable base — shared utilities, project structure, and documentation |
| `node_implementation` | Core Neural ODE implementation using an ODE solver (e.g. `torchdiffeq`) with training loops and evaluation scripts |
| `mnist_comparison` | Comparison of Neural ODE vs. a standard ResNet baseline on the MNIST digit classification benchmark |
| `time_series_comparison` | Application of Neural ODE to irregular time-series data, compared against RNN/LSTM baselines |


```

