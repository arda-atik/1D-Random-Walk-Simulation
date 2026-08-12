# 1D Random Walk Simulation with Python

## 📌 Project Overview
This project presents a simple yet powerful computational model of a **One-Dimensional (1D) Random Walk** using basic Python data structures and `matplotlib`. 

Random walk is a fundamental concept in stochastic processes, extensively used to model real-world phenomena across various fields, including:
* **Quantitative Finance:** Stock price movements (Random Walk Hypothesis / Brownian Motion).
* **Physics:** Molecular diffusion and particle movement.
* **Mathematics & Statistics:** Distance expectations and probability distributions.

## 🛠️ How It Works
1. Starts at an initial position $x = 0$.
2. At each discrete step, a random choice is made to move either $+1$ (forward) or $-1$ (backward) with equal probability $p = 0.5$.
3. The spatial trajectory is recorded across $N = 1000$ steps and plotted over time.

## 🚀 Key Takeaways
Mathematical theory suggests that after $N$ steps, the expected RMS (root-mean-square) displacement from the origin is proportional to $\sqrt{N}$. This simulation visually demonstrates how completely random local decisions create non-trivial global spatial patterns.
