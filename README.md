# Uber Dataset Exploratory Data Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) on a dataset of Uber trips to uncover patterns in trip distances, purposes, categories, and temporal trends.

### Objectives
- Analyze trip distances, categories, purposes,mand temporal patterns.
- Identify high-demand areas, peak times, and trip efficiency.
- Provide actionable insights for Uber (e.g., driver allocation, pricing strategies).


## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Archish1962/HexSoftwares_Exploratory_Data_Analysis.git
   cd HexSoftwares_Exploratory_Data_Analysis
   ```

2. **Set Up Virtual Environment** (recommended):
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the Notebook**:
   Launch Jupyter Notebook:
   ```bash
   jupyter notebook uber_eda.ipynb
   ```
   Run all cells to reproduce the analysis and visualizations.

## Key Insights
- **Trip Distances**: Most trips are short (2–10 miles), with outliers up to ~310 miles.
- **Categories**: ~93% Business trips, reflecting a business-heavy dataset.
- **Purposes**: Meetings (~28%) and Meal/Entertain (~24%) dominate among known purposes.
- **Temporal Patterns**: Peaks during weekday business hours (9:00–17:00, Monday–Friday).
- **Efficiency**: Miles and duration correlate positively, with outliers suggesting traffic or delays.


## Notes
Replace relative paths with file path of visualizations folder