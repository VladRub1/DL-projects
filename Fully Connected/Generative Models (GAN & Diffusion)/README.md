# Generative Models

The [project](./generative-models-practice-RubanovVladislav.ipynb) presents
an implementation of the task of conditional generation of synthetic data for two
Cherenkov telescopes (the [**MAGIC dataset**](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope) — Major Atmospheric Gamma Imaging Cherenkov).

The generation task is conditional with **two classes** of data:
1. Gamma quanta (**photons**)
2. Hadrons (**protons**)

The task is solved using **two types of generative networks**:
1. Generative Adversarial Network (GAN): _Conditional WGAN_
2. Diffusion Model based on the original [DDPM paper](https://arxiv.org/abs/2006.11239)

Additionally, the project includes:
1. _data preprocessing and visualization_
2. writing a _custom loss function_ for Conditional WGAN
3. custom _implementation of architectures_
4. _visualization_ of the training process and results for both models
5. _quality measurement_ of generation

There is also an additional **comparison of model quality** with gradient boosting
by [CatBoost](https://catboost.ai/)nand logistic regression.
