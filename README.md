# occskills

Analysis of occupational skill demands and how they are shifting under AI adoption, using Lightcast job postings data.

The project maps skill requirements across SOC occupations over time to identify which skills are gaining or losing share within occupations, which occupations are most exposed to AI-driven task substitution, and where reskilling investments are best placed. This feeds into broader workforce planning and labor market policy work.

## Data

Source data is Lightcast's occupational skill demand database (not included in this repository). The notebooks expect a cleaned extract in `data/`.

## Contents

```
occskills/
├── notebooks/    # Analysis and charts by occupation group
├── src/          # Skill extraction and trend analysis modules
└── data/         # Input data (not committed)
```

## Setup

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Related work

The skill shift analysis here informs the occupational demand forecasting in [`supply-demand-model`](https://github.com/conway1521/supply-demand-model).
