# Philly-Crime-and-Sports
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) <br></br>
An exploratory data analysis project examining historic Philadelphia crime data in relation to the Philadelphia Eagles’ game schedules and results. This project explores potential patterns, correlations, and insights through data cleaning, visualization, and statistical analysis.

## Project Objective
The goal of this project is to investigate Philadelphia crime incidents from 2016 onward alongside the Philadelphia Eagles’ game schedules and results. Specifically, it asks: Is there a measurable relationship between major sporting events and patterns in city crime data? By combining sports analytics and urban crime data, this project highlights possible connections between community activity and game-day dynamics. 
- Is there a measurable relationship between major sporting events and patterns in city crime data?
- Do crime trends shift on days when the Eagles play, either home or away?
- Are there identifiable correlations (or lack thereof) between crimes and game-day dynamics?
By combining sports data and urban crime data, this project explores possible connections between city crime and football culture.

## Data Sources
- **Philadelphia Crime Data**: [Publicly available](https://data.phila.gov/visualizations/crime-incidents) incident-level reports from the City of Philadelphia.
- **Philadelphia Eagles Schedule & Results**: [NFL-provided historical](https://fixturedownload.com/results/nfl-2025/philadelphia-eagles) schedule and outcomes (2016-present).

## Methods & Tools
- **Languages**: Python (pandas, NumPy, matplotlib, seaborn).
- **Notebook**: Jupyter Notebook (`Philly Crime Data Exploration.ipynb`).
- **Techniques**:
  - Data cleaning and preprocessing.
  - Exploratory data analysis (EDA).
  - Hexbin and scatter visualizations.
  - Statistical correlation testing.

## Key Features
- Combines multiple years of crime data with NFL game datasets.
- Creates visualizations to show patterns in crime density.
- Explores whether crime types decrease, increase, or remain stable during Eagles games.
- Provides reproducible code for further exploration.

## How to Use
1. Clone the repository.
2. Place crime CSVs and Eagles' schedule CSVs in the `/Data` directory (see notebook for expected structure).
3. Open `Philly Crime Data Exploration.ipynb` in Jupyter.
4. Run all cells to reproduce analysis and visualizations.

## Example Visualization
1. Scatter plot of Philadelphia Crimes per Day colored by whether or not Eagles played.
![Scatter Plot](Images/Philadelphia%20Crimes%20per%20Day%20vs%20Eagles%20Games.png)
3. Hexbin map of crime incidents across Philadelphia (by latitude/longitude).
![Hexbin Plot](Images/Philadelphia%20Crime%20Density%20when%20Eagles%20play%20in%20Philly.png)

## Results (Summary)
I found slight correlations between crime and if the Eagles played, but no substantial correlation; specifically in regards to Alcohol related crimes, there was almost no correlation at all. This was surprising because I expected there to be more correlation between Alcohol related crimes and football. At the same time, there was some correlation for Fraud. I believe this is most likely because the Eagles typically play on weekends, and there are less fraud dispatches in the weekends. Other crime types had basically no correation. This highlights the complexity of urban behavior. Ultimately the results emphasized that correlation is not causation, but it can provide insight into social dynamics around major events.

## Potential Next Steps
- Expand dataset to include additional Philadelphia teams and/or more years of data.
- Apply machine learning models to test predictive power.
- Explore demographic and geographic breakdowns.

## License
This project is provided for educational and research purposes. See the LICENSE file for details.
