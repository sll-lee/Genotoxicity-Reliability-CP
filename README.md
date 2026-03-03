# Reliability-Aware Genotoxicity Prediction

This repository contains the implementation of the reliability-aware framework for chemical genotoxicity prediction described in:

Seul Lee et al., "Reliability-Aware Deep Learning Framework for Chemical Genotoxicity Prediction with Uncertainty Quantification", under review.

## Overview

This framework integrates:

- Experimental reliability metadata
- Message Passing Neural Network (MPNN) for credibility estimation
- Reliability-based adaptive sample weighting
- Machine learning classifiers (random forest, SVM, logistic regression)
- Conformal prediction for uncertainty quantification

## Repository Structure

- `Supplementary code_chemical genotoxicity prediction.ipynb`: Main notebook for model training and evaluation.
- `data/`: Dataset files.
- `requirements.txt`: Python dependencies.

## Installation

```bash
pip install -r requirements.txt
```

## Environment

The experiments were conducted using:

- Python 3.7.12
- TensorFlow 2.11.0
- TensorFlow Probability 0.18.0
- NumPy 1.21.6
- pandas 1.3.5
- scikit-learn 1.0.2

Other required packages include nfp and RDKit.

Minor numerical differences may occur depending on the execution environment.
