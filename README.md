# Dive into Deep Learning — Karl's Study Guide 

**Purpose.** After an introductory examination/interview, I realized I had challenges with some technical questions and concepts. It’s been a while since I’ve gone deep into the CS/math side—I’ve been operating more in product/business roles at Microsoft over the last 10 years. However, I'm passionate about rebuilding my foundations.  

This repository is my way to:  
1. Show gratitude by showcasing the work.  
2. Re-learn fundamentals to prepare for a Master’s-level AI program.  
3. Leave a clear, reproducible path for others returning after a gap.  

**Audience.** This is for anyone who once had solid CS fundamentals but stepped away for years and now wants to return to machine learning with structure, momentum, and proof of progress.

---

## What this repo contains 😎

- ✅ **Reproducible environment** (`environment.yml`)  
- 🧠 **Notes** (`notes/`) — chapter summaries in my own words  
- 🧪 **Tiny runnable exercises** (`exercises/`) — small PyTorch/Python demos  
- 📈 **Progress tracking** — each chapter = notes + exercise + PR

I’m following the open textbook **[Dive into Deep Learning (D2L)](https://d2l.ai/)** and capturing both my understanding and runnable examples along the way.

---

## Workflow (per chapter) 

1. **Read** the D2L chapter  
2. **Summarize** — add a short `notes/XX-topic.md` file  
3. **Experiment** — create a small `.py` in `exercises/` (if it makes sense)  
4. **Commit & PR** — merge progress before moving on  

---

## Reach Out 😁 

If you have feedback or questions, feel free to contact me:
Karl Henderson — karl@appblitz.ai

---

## Quickstart (reproduce locally)

```bash
# Create and activate the conda environment
conda env create -f environment.yml
conda activate d2l

# Run an exercise
python exercises/00_env_check.py

 