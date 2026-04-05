# A First Course in Bayesian Statistical Methods (Peter D. Hoff)
## Computational Implementations & Theoretical Applications
This repository is a programmatic deep-dive into the foundations of Bayesian inference. Moving beyond "black-box" libraries, these scripts focus on the first-principles implementation of posterior simulation and predictive modeling.

## 🎯 Project Scope
This project serves as a technical companion to Peter D. Hoff’s curriculum. It bypasses the textbook's inline examples to focus exclusively on original coded solutions for complex exercise problems.

**Mathematical Rigor:** Every script bridges the gap between LaTeX-heavy theory and functional R code.

**Algorithmic Autonomy:** MCMC samplers and Monte Carlo simulations are built from the ground up to ensure a granular understanding of convergence and stochasticity.

**Reproducibility:** set.seed() is strictly implemented across all stochastic workflows to ensure consistent results.

## 🛠 Technical Highlights

**Posterior Estimation:** Implementation of conjugate and non-conjugate prior structures.

**MCMC Frameworks:** From-scratch development of Gibbs Samplers.

**Model Families:** Extensive work with Gaussian, Binomial, and Poisson distributions.

**Predictive Modeling:** Generating posterior predictive distributions to validate model fit against empirical data.

## 📓 Documentation & Data

**The "Analogue" Foundation:** While the code is digital, the logic is born on paper. You can find my [Handwritten Research Notes here](https://drive.google.com/file/d/1CE16Hu46E8y0of6WP7IagFOVoXBkcNwU/view?usp=sharing) (pardon the "technologically challenged" aesthetic).

**Data Sourcing:** Datasets are sourced from [Peter Hoff’s official site.](https://www2.stat.duke.edu/~pdh10/FCBS/Exercises/) In cases where raw files were inaccessible, data was reconstructed via OCR and manual transcription to maintain project continuity.

## 🚀 How to Use

1. Ensure you have R installed.

2. Clone the repo.

3. Each .Rmd file is self-contained with the necessary logic to reproduce the exercise results.

Note: If you spot a "sketchy" derivation or a convergence edge case, feel free to open an issue. Even in the art of blaming—or Bayesian inference—there is always room for a tighter prior.
