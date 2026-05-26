# IPL Analytics

This Jupyter notebook handles data cleaning, calculates key metrics, and exports professional visualizations.

## What's Inside

- **Data Cleaning**: Loads and cleans match data (drops matches with no result, fixes old team name inconsistencies)
- **Toss Impact Analysis**: Calculates how often the toss winner actually ends up winning the game
- **Match Phase Analysis**: Compares scoring across different phases of the innings (Powerplay, Middle Overs, Death Overs)
- **Top Performers**: Shows top batters and bowlers from the recent 5 seasons

## Files You'll Need

- `ipl_analytics.ipynb` - the Jupyter Notebook with the analysis
- `ipl_matches.csv` - your match data file

## Output

Running the notebook creates two chart images:
- `chart1_toss_impact.png` - shows toss win vs toss lose rates
- `chart2_phase_runs.png` - compares runs scored in each phase by winning vs losing teams

## How to Run

Open `ipl_analytics.ipynb` in Jupyter Lab or Jupyter Notebook and run all cells.
