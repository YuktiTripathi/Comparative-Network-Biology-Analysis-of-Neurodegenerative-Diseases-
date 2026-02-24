# Comparative Network Biology Analysis of Neurodegenerative-Diseases

## Overview
This repository contains a comparative systems biology analysis of Alzheimer’s disease, Parkinson’s disease, and Huntington’s disease using protein–protein interaction (PPI) networks. The study aims to identify key hub genes and shared regulatory mechanisms using network topology-based approaches.

## Objectives
1. Construct high-confidence disease-specific PPI networks
2. Analyze network topological properties
3. Identify hub genes using MCC centrality
4. Perform comparative analysis across diseases
5. Visualize conserved and disease-specific regulators

## Tools and Databases
GeneCards
STRING
Cytoscape
cytoHubba
Python (Pandas, Matplotlib)

## Methodology
### 1. Gene Collection
Disease-associated genes were retrieved from GeneCards and ranked by relevance score. The top 150 genes for each disease were selected.
### 2. PPI Network Construction
STRING database was used to generate interaction networks with confidence score ≥ 0.7.
### 3. Network Analysis
Cytoscape NetworkAnalyzer was used to compute degree, density, clustering coefficient, and path length.
### 4. Hub Gene Detection
cytoHubba (MCC method) was applied to identify top 10 hub genes.
### 5. Comparative Analysis
Venn diagrams and cross-disease comparisons were performed using Python.

Comparative analysis revealed FBXO7, FUS, and GRN as conserved hub genes across all three diseases.

## Visualizations
All network figures and comparative plots are available in the figures/ directory.

The study highlights shared molecular mechanisms related to mitochondrial dysfunction, protein homeostasis, and lysosomal regulation, along with disease-specific regulatory architectures.


