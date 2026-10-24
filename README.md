# Biodiversity Patrol Planner (Topic 10)

An educational AI-based habitat patrol planning prototype linked to **SDG 15 (Life on Land)** and **SDG 13 (Climate Action)**.

The prototype uses **synthetic data** and implements:
- CO1: an intelligent patrol agent and PEAS description
- CO2: Uniform-Cost Search and A* route search
- CO3: a ranger allocation CSP with backtracking and forward checking
- CO4: rule-based knowledge representation and inference

## Run

Install Python 3.10+ and execute:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Command-line demo: `python -m src.main`

Tests: `python -m unittest discover -s tests -v`

Sample inputs: `data/sample_habitat.json`.

*This repository contains a simulated classroom prototype, not a deployed conservation system. All patrol lengths, disturbance scores and environmental effects are illustrative.*