# Cricket-Data-Analysis-Using-Python
Analyzed cricket batting statistics using Python, Pandas, Matplotlib, and Seaborn. Performed data cleaning, player performance analysis, career length analysis, and visualized batting records and country-wise statistics.
# Cricket Data Analysis Using Python

## Project Overview
This project analyzes cricket batting statistics using Python, Pandas, Matplotlib, and Seaborn. It explores player performance, batting strike rates, career lengths, highest innings scores, and country-wise batting records through data cleaning, statistical analysis, and visualization.

## Objectives
- Clean and preprocess cricket data.
- Analyze player career lengths and batting averages.
- Compare batting strike rates and highest innings scores.
- Identify top players by highest innings score and career length.
- Analyze hundreds, fifties, and ducks by country.
- Visualize cricket statistics using charts and graphs.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
The dataset `cricket-data.csv` contains cricket player statistics, including matches, batting average, strike rate, highest innings score, fours, sixes, hundreds, fifties, ducks, country, and career span.

## Project Workflow

### 1. Data Cleaning
- Handle missing values.
- Rename columns for better readability.
- Remove unnecessary columns and special characters.
- Split career span into start and end years.
- Extract player names and countries.
- Convert columns to appropriate data types.
- Calculate career length.

### 2. Data Analysis
- Calculate the average career length of cricketers.
- Analyze average batting strike rates for players with careers longer than 10 years.
- Count players whose careers started before 1960.
- Identify the highest innings score by country.
- Explore player performance and career trends.

### 3. Data Visualization
The project includes:
- Distribution of batting strike rates.
- Career length vs. batting average by country.
- Top 10 players by highest innings score.
- Hundreds, fifties, and ducks by country.
- Batting strike rate vs. career length.
- Batting strike rate vs. highest innings score.
- Players with the most hundreds, fifties, and ducks.
- Top cricketers by career length.
- Number of cricketers by career start year.

## Key Insights
This project helps explore differences in batting performance, career longevity, scoring records, and country-wise cricket statistics. Actual findings can be documented after analyzing the dataset.

## How to Run the Project

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Place `cricket-data.csv` in the project directory, open the Jupyter Notebook, and execute the cells sequentially.

## Project Structure

```text
Cricket-Data-Analysis/
├── cricket-data.csv
├── Cricket_Data_Analysis.ipynb
└── README.md
```

## Future Enhancements
- Compare player performance across countries.
- Create interactive cricket dashboards.
- Analyze batting performance across different periods.
- Explore relationships between matches, runs, averages, and strike rates.

## Author
Divya Rahane
