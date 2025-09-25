# Shelf-Layout-Optimization-with-WGAN
- This project explores the use of Generative Adversarial Networks (GANs) — specifically Wasserstein GAN with Gradient Penalty (WGAN-GP) — for generating planograms (shelf layouts) in retail environments.

- The goal is to learn layout distributions from annotated grocery shelf datasets and then generate realistic, constraint-aware layouts that can be used for retail optimization, testing, and augmentation.

## Problem Statement

- Retail shelf layouts (planograms) affect sales, customer attention, and product visibility. Traditional layout design is manual and time-consuming.
We aim to automatically generate shelf layouts using deep generative models, enabling:

- Realistic synthetic planograms for training retail AI systems.

- Exploration of optimal product arrangements under demand or business constraints.

## Objectives

- Parse shelf datasets into structured layouts (bounding boxes of products).

- Train a WGAN-GP model to learn distribution of product placements.

- Generate new feasible shelf layouts (bounding boxes).

- Provide a scalable base for constraint-aware optimization (e.g., demand-driven layouts, no overlaps).
