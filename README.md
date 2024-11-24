# Project Overview

This repository implements and explores the theory of derivative valuation through Python.
The focus is on an easy-to-follow, expository style.

# Project Structure

- `Asian Options`: Outlines the theory and implementation of pricing Arithmetic Asian call options using the Geometric Brownian Motion (GBM) stock process.
The aim is to summarise the different Asian option pricing approaches from existing literature and also discuss some practical implementation details as well as their computational efficiency. 

- `European Options`: Demonstrates the implementation of pricing European call options using two distinct price dynamics: **Geometric Brownian Motion (GBM)** and **Variance Gamma (VG)** models. The focus is on computational methods rooted in Fourier Transform and Fast Fourier Transform (FFT) techniques, guided by the influential paper *"Option Valuation Using the Fast Fourier Transform"* by Carr and Madan (1999).

# Installation & Requirements

To run the notebooks, you will need to have Python installed, along with the following libraries:

- `numpy`
- `scipy`
- `matplotlib`
