# Over or Under Budget?
**LUISS Finance Club (LFC) Quants & IT** | Spring 2026 | **Yasemin Ateş**
Monte Carlo simulations to predict Zohran Mamdani's policies going over or under the budget, with a given threshold. The Mayor's 4 flagship NYC policies:
- City-run Grocery Stores ($63M ±25%)
- Fare-Free MTA Buses ($776M ±$200M)  
- Rent Freeze (72% bundle: $2.5B ±$800M)
- Landlord Emergency Fund (8% trigger: $1.8B crisis)

Key Findings Are: **67% breach probability** at realistic $3B threshold (2.7% of $110B operating budget).


## Results Summary

| Metric | Value | Implication |
|--------|-------|-------------|
| **Mean Cost** | $3.47B | Exceeds $3B cap |
| **Breach Prob** | **69%** | 7/10 years overrun |
| **90% Range** | $2.0B-$5.1B | $4.5B needed for 10% risk |
| **Rent Freeze** | **72%** | Structural driver |

**Rent freeze dominates** - 38× grocery costs. Policies **fiscally unsustainable** without $1B+ revenue buffer amid NYC's $7-12B deficits.[web:78][web:102]

## How to Run

```bash
#--- Clone and Setup
git clone https://github.com/LUISS-Finance-Club/mamdani-nyc-policy-budget-prediction-montecarlo.git
cd mamdani-nyc-policy-budget-prediction-montecarlo

#--- Run Notebook
jupyter notebook notebook.ipynb