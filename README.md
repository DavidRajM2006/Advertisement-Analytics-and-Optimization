# Advertisement-Analytics-and-Optimization
End-to-end advertisement analytics and optimization project using CTR analysis and Multi-Armed Bandit algorithms, developed during a Shaastra 2026 workshop at IIT Madras.

# Advertisement Analytics and Optimization using Multi-Armed Bandits

## Project Overview
This repository contains an end-to-end advertisement analytics and optimization project developed as part of a workshop conducted during Shaastra 2026 at IIT Madras.

The project is structured as a single, coherent pipeline that progresses from understanding advertisement click behavior to applying algorithmic and probabilistic optimization techniques using Multi-Armed Bandits.

---

## Project Structure and Progression

The repository combines four closely related projects, each building on the previous stage.

### Project 1: CTR and Exploratory Data Analysis
This stage focuses on analyzing advertisement click-through rate (CTR) data to understand user behavior, temporal trends, and feature-level performance differences.

Primary focus:
- CTR computation
- Trend analysis
- Feature-based aggregation

---

### Project 2: Observed Reward Analysis (Bandit Perspective)
Building on the CTR insights, advertisements are treated as competing arms in a decision-making framework. Observed rewards (clicks and CTR signals) are analyzed under uncertainty.

Primary focus:
- Reward interpretation
- Performance comparison under uncertainty
- Decision-oriented evaluation

---

### Project 3: Multi-Armed Bandit Algorithms
This stage introduces algorithmic decision-making by implementing core Multi-Armed Bandit strategies that balance exploration and exploitation in advertisement selection.

Primary focus:
- Bandit strategy formulation
- Long-term reward optimization concepts

---

### Project 4: Thompson Sampling Optimization
The final stage extends the bandit framework using Thompson Sampling, a probabilistic algorithm widely used in real-world advertisement systems to improve selection efficiency through Bayesian inference.

Primary focus:
- Probabilistic modeling
- Efficient exploration–exploitation balance

---

Together, these projects form a complete pipeline:
Data understanding → Performance evaluation → Algorithmic optimization → Probabilistic optimization

---

## Dataset
- File: `AdClickInfo.csv`
- Type: Structured tabular dataset
- Used consistently across all four project stages

---

## Repository Structure

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
3. Run notebooks in sequence from `01` to `04`.

---

## Acknowledgement
This project was completed during a workshop conducted as part of Shaastra 2026 at IIT Madras, under the guidance of Sri Vallabha Deevi.

---
