# 📂 COVID-19 Data Analysis and Visualization

## Overview

This project provides an in-depth analysis and visualization of COVID-19 data to uncover trends, insights, and patterns. Using data from the [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv), the analysis focuses on key metrics such as total cases, deaths, vaccination progress, and mortality rates. The project employs Python libraries like Pandas, Matplotlib, Seaborn, and Plotly for data manipulation and visualization.

## Dependencies

To run this project, ensure you have the following dependencies installed:

- Python 3.8 or higher
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

### Step-by-Step Guide to Running the Project

1. **Clone the Repository**:

```sh
git clone https://github.com/dipankarmajumdar/covid-19-data-analysis.git
cd covid-19-data-analysis
```

2. **Install Dependencies**: Run the following command to install all required libraries:

```sh
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**: Start Jupyter Notebook in the project directory:

```sh
jupyter notebook
```

4. **Open the Notebook**: Open the `covid-19-data-analysis.ipynb` file in Jupyter Notebook.
5. **Run the Notebook**: Execute the cells sequentially to load the dataset, clean the data, and generate visualizations.

### Key Findings and Insights

1. **Top 10 Countries by Total Cases and Deaths**:

- The analysis identifies countries with the highest total cases and deaths, providing insights into the global impact of COVID-19.

2. **Global Trends**:

- Visualizations show the progression of total cases and vaccination efforts over time.

3. **Mortality Rates**:

- A comparison of mortality rates across countries highlights regions with higher fatality rates.

4. **Vaccination Progress**:

- Interactive maps and bar plots reveal the vaccination progress globally and by country.

5. **Country-Specific Trends**:

- Detailed analysis of daily new cases for specific countries, such as India.

## Directory Structure

```sh
COVID-19 Data Analysis and Visualization/
│
├── covid-19-data-analysis.ipynb
├── requirements.txt
├── data/
│   └── owid-covid-data.csv
└── README.md
```

## File Organization

1. `covid-19-data-analysis.ipynb`:

- The main notebook containing all the code for data analysis and visualization.

2. `requirements.txt`:

- A file listing all the Python libraries required to run the project.

3. `data/owid-covid-data.csv`:

- The dataset used for analysis, sourced from [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv).

## Visualizations

The project includes the following visualizations:

- Bar plots for top 10 countries by total cases, deaths, and vaccination rates.
- Line plots for global trends in cases and vaccinations.
- Interactive scatter plots and choropleth maps using Plotly.

## How to Contribute

Contributions are welcome! If you'd like to improve the analysis or add new features:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Data Source: [Our World in Data](https://covid.ourworldindata.org/data/owid-covid-data.csv)
- Libraries: Pandas, Matplotlib, Seaborn, Plotly

```sh
This `README.md` provides a comprehensive overview of the project, making it easy for others to understand and use your work.
```
