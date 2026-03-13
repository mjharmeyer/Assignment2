# README

## Requirements

* **Python 3.x**
* **Packages**: `pandas`, `numpy`, `scipy`, `openpyxl`

```bash
pip install pandas numpy scipy openpyxl

```

## Setup

Place the following files in the same directory as the script:

* `car.data`
* `communities.data`
* `default of credit card clients.xls`

## Execution

Run the script using:

```bash
python main.py

```

## Output Interpretation

* **Level k Table**: Compares candidate generation counts between the brute-force ($F_{k-1} \times F_1$) and prefix-join ($F_{k-1} \times F_{k-1}$) methods to show efficiency gains.
* **Frequent Itemsets**: Total count of itemsets meeting the minimum support threshold.
* **Association Rules**: Lists top rules by **Lift** for three confidence levels (0.5, 0.7, 0.9).
* **Confidence**: Probability of the consequent given the antecedent.
* **Lift**: Strength of the correlation (>1 indicates a positive relationship).



Would you like me to adjust the support thresholds in the code before you finalize?
