# COVID-19 Global Data Tracker

## Project Description
A data analysis and visualization project tracking global COVID-19 trends including cases, deaths, recoveries, and vaccination progress. This Jupyter Notebook provides insights into the pandemic's progression across different countries through interactive visualizations and data analysis.

## Objectives
- Import and clean global COVID-19 data from reliable sources
- Analyze time trends in cases, deaths, and vaccinations
- Compare metrics across countries and regions
- Visualize trends with charts and maps
- Communicate findings through an interactive notebook

## Tools & Libraries Used
- **Python 3** (Jupyter Notebook environment)
- **Data Processing**: pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly Express
- **Optional**: GeoPandas (for advanced mapping)
- **Data Sources**: Our World in Data COVID-19 Dataset

## How to Run/View the Project

### Prerequisites
- Python 3.8+
- Jupyter Notebook/Lab
- Required Python packages (install via `pip install -r requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Ancentian/covid-19-tracker.git
   cd covid-19-tracker
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset:
   - Manual download from [Our World in Data](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv)
   - Save as `owid-covid-data.csv` in the project root

### Running the Notebook
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Key Insights
1. **Vaccination Inequality**: Developed nations achieved vaccination rates 3-5x higher than developing nations within the same timeframe.
2. **Wave Patterns**: Most countries experienced 3-4 distinct waves of infection, often correlating with new variants.
3. **Fatality Rates**: Case fatality rates varied significantly (0.5%-3.5%) based on country healthcare capacity and demographics.
4. **Data Gaps**: Many countries showed irregular reporting patterns, particularly in early pandemic stages.

## Reflections
Building this project revealed several important lessons:
- **Data Quality Matters**: Cleaning and preprocessing took significant effort but was crucial for accurate analysis
- **Visualization is Powerful**: Interactive maps and time-series plots made patterns immediately apparent
- **Global Perspective is Valuable**: Comparing countries highlighted how different policies affected outcomes
- **Pandemic Evolution**: The data clearly shows how the pandemic characteristics changed over time

## Future Enhancements
- Add automated data refreshing from the API
- Include more socioeconomic factors in the analysis
- Build predictive models for future trends
- Create an interactive dashboard version

## Acknowledgements
Data provided by [Our World in Data](https://ourworldindata.org/coronavirus)
