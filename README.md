# Validation-of-Attribution-Scores
This repository includes the codes that were used to compute the attribution scores and AOPC in Pinto Jr &amp; Shin (under review)
## Overview
This repository contains the code and resources associated with the study titled *Validation Study of Attribution Scores Usage in Explainable Automated Scoring Systems*. This study investigates the use of attribution scores in Automated Short Answer AES systems, examining their consistency in reflecting model decisions. We employ a quantitative approach to assess the convergence or divergence of attribution methods, such as LIME, and IG, on a publicly available dataset. compares several computational approaches for measuring linguistic synchrony in one-to-one educational tutoring environments, focusing on Algebra and Language tutoring conversations.
## Methods
The following attribution scores methods are implemented in this repository:
- Representation Erasure (or leave-one-out; LOO) (Li, Monroe, & Jurafsky, 2016): tokens are systematically erased to determine their contribution to prediction accuracy.
- Local Interpretable Model-agnostic Explanations (LIME) (Ribeiro et al., 2016): estimates individual word contribution locally by training a local surrogate model (typically linear regression) to explain individual predictions from perturbed examples.
- Integrated Gradients (IG)(Sundararajan et al., 2017): an axiomatic approach that consider the straight line path from the baseline x' to the input x, and computes the gradients at all points along the path.
- Hierarchical Explanation via Divisive Generation (HEDGE) (Chen, Zheng and Ji, 2020): builds hierarchical explanations by recursively detecting the weakest interactions and then dividing large text spans into smaller ones based on the interactions.
## Installation
Clone the repository:

git clone https://github.com/your-repo/synchrony-computation.git
cd synchrony-computation

Set up the virtual environment and install required packages:



## Data

## Usage

