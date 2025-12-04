# Analysis and Discussion on Over-Squashing in MPNNs

This repository contains the code and material used for our study  
**“Analysis and Discussion on Over-Squashing in Message Passing Neural Networks:  
The Impact of Width, Depth, and Topology.”**

## Contents

- **Main Jupyter notebook**  
  The full implementation of the experiments (data generation, model definition, training and plotting) is contained in the main Jupyter notebook (the one shown in the repository preview/screenshot).  
  This notebook reproduces the figures and results discussed in the report, including:
  - synthetic dataset generation (trend + periodic signals),
  - GAT/GATv2-based autoencoder architecture,
  - star-graph experiments with varying numbers of central nodes,
  - analysis of reconstruction error and loss curves.

- **PDF report**  
  The associated written report (the PDF file shown in the repository) presents:
  - a review and discussion of the paper by Di Giovanni et al. on over-squashing,
  - the theoretical background (sensitivity, obstruction Jacobian, commute time, Cheeger constant),
  - our complementary perspective on **topological expressivity bottlenecks**,
  - the experimental setup and results of the star-graph GAT autoencoder.

## How to use

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd <repo-folder>
