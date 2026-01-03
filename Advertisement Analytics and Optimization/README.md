# Advertisement Analytics and Optimization using Multi-Armed Bandits

## Project Overview
This repository presents a complete advertisement analytics and optimization pipeline composed of four
closely related projects. Together, they demonstrate a clear progression from descriptive data analysis
to algorithmic decision-making and optimization using Multi-Armed Bandit techniques.

The projects are intentionally combined into a single repository to reflect a realistic, end-to-end
workflow used in data-driven advertising systems.

---

## Relationship Between the Projects

### Project 1: CTR and Exploratory Data Analysis
This project establishes the foundation by analyzing advertisement click data.
It focuses on understanding click-through rate (CTR) behavior, temporal trends,
and feature-level performance differences.

Key question addressed:
What patterns and behaviors exist in advertisement interaction data?

---

### Project 2: Observed Reward Analysis using a Bandit Perspective
Building on the CTR insights, this project reframes advertisements as competing
arms in a decision-making problem.
Observed rewards (clicks and CTR signals) are analyzed under uncertainty.

Key question addressed:
How should advertisement performance be evaluated when outcomes are uncertain?

---

### Project 3: Multi-Armed Bandit Algorithms
This project advances from observation to action.
It introduces and evaluates core Multi-Armed Bandit strategies that balance
exploration and exploitation for advertisement selection.

Key question addressed:
How can advertisement selection be optimized over time using bandit algorithms?

---

### Project 4: Thompson Sampling for Bandit Optimization
The fourth project extends the bandit framework by implementing Thompson Sampling,
a probabilistic algorithm widely used in real-world ad systems.
It demonstrates how Bayesian methods improve decision-making efficiency and reward optimization.

Key question addressed:
How can probabilistic modeling further improve advertisement selection strategies?

---

Together, these projects form a coherent pipeline:
Data understanding → Performance evaluation → Algorithmic optimization → Probabilistic optimization

---

## Repository Structure
```
data/
 └── raw/
     └── AdClickInfo.csv

notebooks/
 ├── 01_DataAnalysis.ipynb
 ├── 02_MAB_ObservedData.ipynb
 ├── 03-MultiArmedBandits.ipynb
 └── 04-MultiArmedBandits-ThompsonSampling.ipynb

outputs/
 ├── figures/
 └── reports/

README.md
requirements.txt
```

---

## Tech Stack
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Launch Jupyter Notebook:
   jupyter notebook

3. Run notebooks in sequence:
   - 01_DataAnalysis.ipynb
   - 02_MAB_ObservedData.ipynb
   - 03-MultiArmedBandits.ipynb
   - 04-MultiArmedBandits-ThompsonSampling.ipynb

---

## License
MIT License
