## Week 2 Problem Set — Answers

### Problem 1: Why must data be mean-centered before PCA?
PCA finds directions of maximum variance. If data is not mean-centered, the first principal component may simply point toward the mean rather than capturing true variance directions.

### Problem 2: PCA preserves variance but not class separability
Two classes may overlap in high-variance directions but differ in low-variance ones. PCA keeps variance, not discriminative power, so class separation may worsen.

### Problem 3: t-SNE clusters well but classifiers perform poorly
t-SNE preserves local neighborhoods, not global structure. Clusters look clean in 2D, but distances are distorted, so classifiers trained on t-SNE embeddings generalize poorly.
