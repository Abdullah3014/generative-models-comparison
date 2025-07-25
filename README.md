# Generative Models Comparison: VAE, GAN, and Diffusion

This repository provides a unified empirical framework to simulate and compare three major generative model families on synthetic 2D Gaussian Mixture data:

- **Variational Autoencoders (VAEs)**
- **Generative Adversarial Networks (GANs)**
- **Diffusion Models (DDPM-style)**

The code is lightweight, runs in Google Colab or locally with Python, and produces reproducible plots ready for academic manuscripts.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `generative_ai_comparison.py` | Full simulation script comparing VAE, GAN, and Diffusion |
| `vae_loss_curve.png` | VAE training loss over epochs |
| `vae_generated_vs_real.png` | VAE-generated samples vs real data |
| `gan_generated_vs_real.png` | GAN-generated samples vs real data |
| `diffusion_generated_vs_real.png` | Diffusion-generated samples vs real data |
| `training_time_comparison.png` | Bar chart comparing training times |
| `all_models_samples.png` | Overlay of real vs generated samples from all models |
| `README.md` | This file |
| `requirements.txt` | Dependencies to run the script |

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/generative-models-comparison.git
cd generative-models-comparison

