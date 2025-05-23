# Pass Rusher Market Valuation Model

This repository presents a data-driven methodology for profiling NFL pass rushers and estimating their market value using statistical performance metrics. It blends sports analytics with predictive modeling to support more objective contract valuation and talent evaluation in the NFL.

---

## Project Overview

This model is designed to quantify the on-field value of NFL edge defenders by analyzing key performance indicators and estimating what they should be paid relative to market benchmarks. The ultimate goal is to identify potential contract inefficiencies and project fair valuations based on player profile clusters and predictive regression techniques.

---

## Key Features

* **Player Profiling:** Clusters edge defenders by similar performance patterns and roles.
* **Market Valuation:** Predicts expected contract value using regression-based methods and historical signing data.
* **Data Cleaning & Preparation:** Ensures consistency and accuracy in advanced defensive metrics across multiple seasons.
* **Visualization:** Uses plots to communicate trends in player valuation, cluster characteristics, and feature importance.

---

## Methods Used

* KMeans clustering (or other unsupervised grouping methods)
* Linear and Ridge Regression
* Scikit-learn preprocessing pipelines
* NFL performance data (e.g., pressures, sacks, win rate)
* Contract data from verified sports contract databases

---

## Repository Structure

```
PassRusherProfile/
│
├── data/                   # Cleaned and processed datasets
├── models/                 # Trained models and weights (if committed)
├── notebooks/              # Jupyter notebooks for exploration and visualization
├── scripts/                # Core model training and clustering code
├── visuals/                # Output plots and graphics
├── requirements.txt        # List of Python packages used
├── README.md               # Project documentation
└── .gitignore
```

---

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/PetersQuinn/PassRusherProfile.git
   cd PassRusherProfile
   ```

2. **Install required packages:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run notebook or script:**
   Use the provided notebooks or `scripts/` files to explore clustering, modeling, and valuation.

---

## Status

 **Player clustering model complete**
**Initial regression models tested**
**Feature weighting and advanced validation ongoing**
**Potential extension: Include team scheme context or injury history**

---

## Author

**Quinton Peters**
B.S.E. Candidate, Risk, Data, and Financial Engineering
Duke University
[@PetersQuinn](https://github.com/PetersQuinn)
