# Energy Price Pass-Through to Core Inflation in the Euro Area

This notebook investigates whether changes in energy prices (Brent crude oil) affect core inflation in the euro area and whether this relationship changed after the post-2021 inflation episode. It compares two periods (2015–2019 and 2021–2024) using cross-correlation analysis and OLS regression.

## Requirements

Install the required Python packages: `pip install pandas numpy matplotlib statsmodels fredapi`

## Data

Brent crude oil prices are downloaded automatically using the the FRED API. Get a free API key at [fred.stlouisfed.org](https://fred.stlouisfed.org) and set it as an environment variable before starting Jupyter (`set FRED_API_KEY=yourkey` (Windows) or `export FRED_API_KEY=yourkey` (Mac/Linux)). Then start Jupyter from the same terminal window. 

Core inflation (HICP) data is not included in this repository due to file size. Download `estat_prc_hicp_midx.tsv` directly from [Eurostat](https://ec.europa.eu/eurostat/databrowser/product/view/PRC_HICP_MIDX).

## Usage

Place `estat_prc_hicp_midx.tsv` in the same folder as the notebook, set your 
FRED API key, and run all cells.
