# Capstone Project: Data Analysis of Job Trends and Programming Skills (2019)

## Overview
This project focuses on analyzing job trends and programming skills required for developers in the year 2019. It aims to practice essential data analyst skills, including data collection, exploration, wrangling, analysis, visualization, and dashboard creation.

## Project Structure
- **data_collection/**: Directory for data collection scripts and their output files.
  - `Collecting_jobs_using_APIs.ipynb`: Notebook for collecting job data using APIs.
  - `job_postings.xlsx`: Output Excel file from the API data collection notebook.
  - `Collecting_jobs_using_web_scraping.ipynb`: Notebook for collecting job data using web scraping.
  - `popular-languages.csv`: Output CSV file from the web scraping notebook.
- **data_wrangling/**: Directory for data wrangling notebooks.
  - `Data_wrangling.ipynb`: Notebook for cleaning and preparing the data.
- **exploratory_data_analysis/**: Directory for exploratory data analysis notebooks.
  - `Exploratory_Data_Analysis.ipynb`: Notebook for exploratory data analysis and visualization.
- **visualization/**: Directory for visualization notebooks.
  - `Data_Visualization.ipynb`: Notebook for creating visualizations.
- **dashboard/**: Directory for the dashboard PDF file.
  - `Dashboard.pdf`: Dashboard presenting the results of the analysis with 8 graphs.
- `README.md`: Project README file.

## Dependencies

- Python 3.x
- pandas
- matplotlib
- seaborn
- requests
- openpyxl
- BeautifulSoup (for web scraping)
- sqlite3
- Other dependencies...

## Instructions

To run the notebooks, follow these steps:

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Open each notebook in Jupyter Notebook or JupyterLab.
3. Execute the code cells in sequential order.

### Data Collection

- **`Collecting_jobs_using_APIs.ipynb`**: This notebook collects job data related to specified technologies and locations using an API. The results are saved to an Excel file `job_postings.xlsx`.
- **`Collecting_jobs_using_web_scraping.ipynb`**: This notebook scrapes data from a webpage about programming languages and saves the results to a CSV file `popular-languages.csv`.

### Data Wrangling

- **`Data_wrangling.ipynb`**: This notebook handles data cleaning tasks such as removing duplicates, handling missing values, and normalizing data.

### Exploratory Data Analysis

- **`Exploratory_Data_Analysis.ipynb`**: This notebook performs exploratory data analysis, including visualizing data distributions, calculating statistical summaries, and handling outliers.

### Data Visualization

- **`Data_Visualization.ipynb`**: This notebook includes various visualizations, such as histograms, box plots, scatter plots, bubble plots, pie charts, stacked charts, line charts, and bar charts, to provide insights into the data. The data set is presented in the form of a RDBMS, and SQL queries are used to extract the data.

### Dashboard

- **`Dashboard.pdf`**: This PDF file made with IBM Cognos Analytics contains a dashboard with graphs that provide an overview of the survey analysis results.

## Results

The Stack Overflow Developer 2019 Survey analysis revealed several key findings, including:

- JavaScript tops both current usage and future expectations as the most utilized and desired programming language.
- MySQL leads in current database usage, while PostgreSQL emerges as the most desired database for the upcoming year.
- Linux dominates both present platform usage and future aspirations among developers.
- jQuery is prevalent in current web framework usage, with React.js being the most desired for the next year.
- Men represent 93% of the survey respondents.
- The majority of respondents hail from the United States and Canada.
- A significant proportion of respondents hold bachelor's or master's degrees in Computer Science, Computer Engineering, or Software Engineering.
- The majority of respondents fall within the age range of 20 to 34 years old.
