# Can Money Buy Wins? (DTSC 2302 Group 21)

Open `mlb_models.ipynb` in VS Code (install the **Python** and **Jupyter** extensions) and run the cells top to bottom.
Install packages once: `pip install -r requirements.txt`

## Files
| File | What it is |
|---|---|
| `mlb_models.ipynb` | The whole project: data → Ridge Regression → Random Forest → Gradient Boosting → comparison |
| `data/teams.csv` | Wins and losses, 2001–2016 (Lahman Baseball Database, SABR: https://sabr.org/lahman-database/) |
| `data/salaries.csv` | Player salaries, 2001–2016 (Lahman; salaries end in 2016) |
| `data/metro_gdp.csv` | Created on first run: real GDP and GDP per capita by metro from FRED (https://fred.stlouisfed.org, series `RGMP<code>` and `PCRGMP<code>`; original source BEA). Needs internet once; no API key. |
| `data/team_seasons.csv` | Created on run: the final merged dataset |
| `data/model_results.csv` | Created on run: accuracy of every model |
