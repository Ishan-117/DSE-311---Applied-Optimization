# DSE-311 — Applied Optimization

This repository contains the implementation of a **Robust Daily Aircraft Routing Problem (DARP)** based on a research paper by Deng et al. (2022). The goal is to assign a fleet of aircraft to daily flight legs while minimizing operating costs and improving resilience to delays.

We have implemented and compared the following two models:

- **Model 1: Deterministic MILP**  
  Assigns aircraft to flight sequences minimizing total operating cost.

- **Model 2: Game-Theoretic Robust MILP**  
  Extends Model 1 to minimize the worst-case delay propagation cost under a single-leg disruption.

## Repository Contents

- 📁 `Aircraft_Routing.ipynb` — Jupyter notebook containing full Python implementation  
- 📄 `presentation.pdf` — Presentation slides  
- 📝 `report.pdf` — Final project report  
- 📚 `paper.pdf` — Research paper the project is based on

## Reference Paper

**Title:** A Game-Theoretic Approach for the Robust Daily Aircraft Routing Problem  
**Authors:** Zhicheng Deng, Lavindra de Silva, Pascal Van Hentenryck  
**Journal:** *Journal of Mathematics*, 2022  
**DOI:** [10.1002/mma.7920](https://doi.org/10.1002/mma.7920)  
**PDF:** [Download from Wiley](https://onlinelibrary.wiley.com/doi/10.1002/mma.7920)

## Technologies Used

- Python 3.11  
- PuLP (MILP modeling)  
- CBC Solver  
- NetworkX (graph generation)  
- Matplotlib / Seaborn (visualizations)  

---

**Course:** DSE-311 — Applied Optimization  
**Team Members:** [Ishan Thoke, Sushrut Jog, Akshi Jain, Harshal Badge]
