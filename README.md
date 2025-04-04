# Weather Events and Insurance Market Analysis

## Project Overview
This research project investigates the "Influence of extreme climatic conditions on insurance companies stock prices" under the supervision of Dr. Bernstein. The analysis explores the relationship between severe weather events (tornados and storms) and the performance of insurance-related ETFs, specifically the iShares U.S. Insurance ETF (IAK).

## Research Question
Does the occurrence and intensity of extreme weather events (tornados and hurricanes) correlate with changes in insurance company stock prices?

## Data Sources
The project uses multiple datasets located in the `data/` directory:

- **Insurance Data**: 
  - `insurance.csv` - Contains historical price data for the iShares U.S. Insurance ETF (IAK)
  
- **Weather Event Data**:
  - `us_tornado_dataset_1950_2021.csv` - Historical tornado data from 1950-2021
  - `tornados.csv` - Additional tornado data with more detailed attributes
  - `storms.csv` - Hurricane and tropical storm data

## Key Features
- Time series analysis of weather events and stock prices
- Correlation analysis between extreme weather events and market performance
- Visual exploration of weather patterns and their potential financial impact
- Analysis of different categories of storms and their frequency

## Project Structure
```
AlgoTesting/
├── data/                      # Data directory
│   ├── insurance.csv          # Insurance ETF price data
│   ├── tornados.csv           # Tornado dataset
│   ├── storms.csv             # Hurricane dataset
│   └── us_tornado_dataset_1950_2021.csv  # Historical tornado data
│
├── models/                    # Model directory (empty)
│
├── sample.ipynb               # Main analysis notebook
│
└── requirements.txt           # Project dependencies
```

## Preliminary Findings
- The correlation between tornado occurrences and the IAK ETF adjusted close prices appears to be very weak (approximately 0.02)
- Time series analysis shows no clear pattern between weather events and immediate market reactions
- Analysis of Category 5 storms was attempted but encountered data limitations

## Dependencies
The project requires the following packages:
- pandas (2.0.3)
- numpy
- seaborn
- matplotlib

## How to Use This Repository
1. Clone the repository
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open `sample.ipynb` to see the complete analysis, visualizations, and findings
4. Explore the various datasets in the `data/` directory to understand the raw data used

## Future Work
- Develop predictive models to forecast insurance market movements based on weather patterns
- Expand the analysis to include more types of extreme weather events
- Incorporate additional financial metrics beyond stock prices
