# Wasserstein Diffusion on the Annotation Simplex

### Improving Diffusion-Based Video Summarization

**Author:** Milind Sahu  
**Institution:** IISER Tirupati

---

## Abstract

This project proposes a geometric correction to diffusion-based video summarization.

The original framework aggregates multiple annotators using an arithmetic mean. This proposal argues that annotation scores live on a probability simplex and should instead be combined using Wasserstein geometry.

---

## Proposed Improvements

### 1. Wasserstein Barycenter
Replace arithmetic averaging with an optimal transport consensus.

### 2. Dirichlet Noise
Ensure noisy states remain valid probability distributions.

### 3. Wasserstein Loss
Introduce geometry-aware supervision.

---

## Expected Outcome

Improved summary quality on:

- TVSum
- SumMe
- FPVSum

---

## Paper

📄 [Read the Proposal](./RESEARCH_PROPOSAL_IIITK.pdf)

---

## Author

Milind Sahu  
BS-MS Mathematics  
Indian Institute of Science Education and Research Tirupati
