# Efficient Portfolio Selection with Multi-Objective Optimization

This repository contains the **datasets, results, and supplementary material** related to the article:

> **Efficient selection of investment portfolios in complete real-world markets: a multi-objective optimization approach**  
> *Antonio J. Hidalgo-Martín, Antonio J. Nebro, José García-Nieto*  
> Submitted to *Applied Intelligence Journal*

## 📄 Overview

The study addresses the complex problem of portfolio optimization in real-world markets using **multi-objective metaheuristics**. We aim to identify investment portfolios that maximize expected return while minimizing risk, modeled as a **bi-objective optimization problem**.

We evaluate four state-of-the-art metaheuristic algorithms:

- NSGA-II  
- MOEA/D  
- SMS-EMOA  
- SMPSO

The approach is validated on **real market data** collected from over 11,000 assets listed on major U.S. exchanges (NYSE, NASDAQ, ARCA, AMEX, BATS, OTC), covering a variety of liquidity and sectoral profiles.

---

## 📊 What’s in this repository?

This repository includes:

- 🧾 **Returns and Covariance Matrices**: Processed inputs used to define each optimization instance.
- ⚙️ **Experimental Results**: Output files with Pareto fronts, performance indicators, and representative portfolios.
- 📈 **Benchmark Scenarios**: Problem instances varying in asset selection size and market segmentation.
- 📂 **Dataset descriptions**: Details on how assets were filtered and grouped (e.g. NYSE_5_100, ALL_20_6000).

---

## 🔍 Highlights of the Article

- A new representation for investment portfolios using continuous real-valued vectors.
- Use of **real financial data** (not synthetic benchmarks).
- Implementation based on the [jMetal](https://github.com/jMetal/jMetal) optimization framework.
- Comparative analysis of metaheuristics using indicators such as **Hypervolume (IHV)** and **IGD+**.
- Exploration of high-return, low-risk, balanced, and sectoral portfolios for different investor profiles.

---

## 📁 Folder Structure

```
.
Portfolio_Study/
├── R/                  # R scripts for statistical analysis and visualization
├── sources/            # Processed returns and covariance matrices per instance
├── data/               # Results files for each algorithm and instance
├── html/               # HTML visualizations and interactive plots for metrics
├── latex/              # LaTeX source for tables and figures for metrics
├── referenceFronts/    # Approximated Pareto fronts per algorithm
├── README.md
└── LICENSE
```

---

## 📚 Citation

If you use this repository, please cite the following work:

```
@article{Hidalgo2025Portfolio,
  title={Efficient selection of investment portfolios in complete real-world markets: a multi-objective optimization approach},
  author={Antonio J. Hidalgo-Martín and Antonio J. Nebro and José García-Nieto},
  journal={Applied Intelligence},
  year={2025},
  note={Under review}
}
```

---

## 📬 Contact

For questions or collaboration:

- Antonio J. Hidalgo-Martín — [GitHub](https://github.com/AntHidMar)
- 📧 Email: [anthidmar@uma.es](mailto:anthidmar@uma.es)

---

## 📝 License


This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

Under the following terms:

- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.

More details: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)


---
