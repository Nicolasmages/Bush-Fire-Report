# Bushfire Risk Analysis

## Project Description
This project conducts a comprehensive analysis of bushfire risks in Greater Sydney. Utilizing datasets from open data sources and the NSW Rural Fire Service, we calculate bushfire scores considering factors like population density, dwelling, business locations, and assistive services. Additionally, we explore the correlation between median income and median rent costs across neighbourhoods.

## Data Sources
- NSW Rural Fire Service: Bushfire risk categories
- Open Data NSW: Additional datasets

## Setup and Installation
### Requirements
- PostgreSQL
- Python (Pandas, Geopandas, Matplotlib, Seaborn, etc.)
- PgAdmin

### Installation Steps
1. Clone the repository.
2. Install the required Python packages: `pip install -r requirements.txt`.
3. Set up a PostgreSQL database and use the provided SQL scripts to create and populate tables.

## Usage
- Execute the Python scripts for data cleaning, transformation, and analysis.
- SQL queries can be run in PgAdmin to explore the database.

## Data Analysis Components
- Data Cleaning and Loading
- Fire Risk Score Calculation
- Correlation Testing with Median Income and Rent Costs
- Geospatial Analysis using geopandas

## Results
The analysis results in a comprehensive understanding of bushfire risks in relation to various socio-economic factors. Findings include:
- Fire risk scores by neighbourhood
- Correlations between income levels, rental costs, and bushfire risks
- Geospatial distribution of risks and resources

## Authors
- [Kezhen Zhong]

## Acknowledgments
- NSW Rural Fire Service
- Open Data NSW

