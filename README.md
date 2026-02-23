# Monte Carlo simulation to option pricing in CUDA

## Introduction

This repo contains an implementation of pricing financial derivatives using Monte Carlo simulation with CUDA (Compute Unified Device Architecture).

## Environment

- **GPU** : NVIDIA GeForce RTX 3050 (6GB)
- **CUDA toolkit** : 13.1.1
- **CPU** : 12th Gen Intel(R) Core(TM) i5-12500H, 2500 Mhz
- **RAM** : 16GB DDR5
- **IDE** : Microsoft Visual Studio Version 1.109.5

## Features

- European Call option pricing  
- CPU implementation  
- GPU implementation using CUDA  
- Performance comparison  
- Configurable number of simulations  

## How It Works

1. Generate random stock price simulations  
2. Compute payoff for each simulation  
3. Average the results  
4. Discount to obtain present value  

