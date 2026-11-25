# Interactome-based versus Transcriptomic Representations for Single-cell Classification of Breast Epithelium

## Overview

This project presents a computational pipeline for the classification of human breast epithelial cells using single-cell gene expression data and protein–protein interaction (PPI) information.

The main objective is to compare two feature representations for cell type classification:

- **Gene Expression (GE):** classification based exclusively on transcriptomic features.

- **Gene Expression + Protein–Protein Interactions (GE + PPI):** classification incorporating interactome-based features derived from gene expression and protein interaction networks.

In addition to evaluating classification performance, the project explores the interpretability of interactome-based representations using SHapley Additive exPlanations (SHAP).

## AIMS
- **Generalization:** Does it work on unseen donors and labs?
- **Performance:** Can it compete with expression alone?
- **Interpretability:** Does the interactome make the classifier easier to interpret?

## Dataset
The study focuses on three major human breast epithelial cell populations:
<p align="center">
  <img src"breast_epithelium.png" width="650">
</p>
