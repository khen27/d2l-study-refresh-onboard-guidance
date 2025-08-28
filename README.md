# Dive into Deep Learning — Study Log (Karl Henderson)

**Purpose.** After an introductory examination/interview, I realized I had challenges with some technical questions and concepts. It’s been a while since I’ve gone deep into the CS/math side—I’ve been operating more in product/business roles at Microsoft over the last 10 years, however I'm very passionate about figuring this out. I’m using this repository to (1) show gratitude by showcasing the work, (2) rebuild my foundations for a Master’s-level AI program, and (3) leave a clear, reproducible path for others returning to the field after a gap.

**Audience.** This is for anyone who once had solid CS fundamentals but stepped away for years and now wants to come back to machine learning with structure, momentum, and proof of progress.

---

## What this repo contains

- ✅ **Reproducible environment** via `environment.yml` (Conda + pip)  
- 🧠 **My notes** in Jupyter notebooks (summaries in my own words)  
- 🧪 **Tiny runnable experiments** (PyTorch, plots, sanity checks)  
- 📈 **Clear progress tracking** and small, focused commits/PRs

I’m following the open textbook **[Dive into Deep Learning (D2L)](https://d2l.ai/)** and working primarily in **Jupyter** so reading + code execution stay in one place.

---

## Quickstart (reproduce locally)

```bash
# Create and activate the conda environment
conda env create -f environment.yml
conda activate d2l

# Launch notebooks
jupyter notebook notebooks/00_env_check.ipynb

