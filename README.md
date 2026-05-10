# Market Basket Analysis — Retail Transaction Associations

**WGU MSDA D212 Task 3 | Jared Medlin | September 2025**

## Overview

Market Basket Analysis using the Apriori algorithm to identify purchasing 
associations between products in a retail transaction dataset, with 
actionable recommendations for product placement and cross-selling.

## Research Question

Can Market Basket Analysis identify meaningful customer purchasing 
association behavior?

## Key Results

**Top association rules by metric:**

| Metric | Antecedent | Consequent | Value |
|--------|-----------|------------|-------|
| Confidence | 10ft iPhone Charger Cable 2-Pack | Dust-Off Compressed Gas 2-Pack | 0.456 |
| Lift | VIVO Dual LCD Monitor Desk Mount | SanDisk Ultra 64GB Card | 2.291 |
| Support | Dust-Off Compressed Gas 2-Pack | VIVO Dual LCD Monitor Desk Mount | 0.060 |

**Key finding:** Auxiliary peripheral items (compressed gas, SD cards) 
appear as frequent co-purchases across many product combinations, 
suggesting checkout placement or cart recommendation opportunities.

## Tools & Methods

- **Language:** Python 3 (Jupyter Notebook)
- **Libraries:** pandas, mlxtend
- **Techniques:** Apriori algorithm, association rule mining, 
  support / confidence / lift evaluation

## Repository Contents

| File | Description |
|------|-------------|
| `JaredMedlinD212Task3.pdf` | Full written analysis report |
| `D212Task3.ipynb` | Jupyter Notebook with code and outputs |
| `data/` | Cleaned and raw retail transaction datasets |
