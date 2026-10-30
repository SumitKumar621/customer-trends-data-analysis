# Customer Behavior Data Analysis

## About the Project

In this project, I analyzed customer shopping behavior to understand how customers make purchasing decisions, which customer segments contribute to sales, and what factors influence their shopping patterns.

I worked on different stages of the data analysis process, starting with data cleaning and exploration in Python, followed by SQL queries to answer business-related questions. I also used Power BI to create an interactive dashboard to visualize the results.

The main objective of this project was to practice data analysis using Python, SQL, and Power BI and understand how data can be used to generate useful business insights.

## Tools and Technologies

- **Python:** Data cleaning, preprocessing, and exploratory data analysis.
- **Pandas:** Working with the dataset and performing data transformations.
- **Jupyter Notebook:** Writing and executing Python code.
- **PostgreSQL:** Storing the data and analyzing it using SQL queries.
- **Power BI:** Creating an interactive dashboard to visualize customer behavior.
- **Gamma AI:** Preparing a presentation based on the project findings.

## Project Workflow

### 1. Data Import and Exploration

I started by importing the customer shopping dataset into Python using Pandas. I explored the dataset to understand its structure, columns, data types, and overall characteristics.

### 2. Data Cleaning and Preprocessing

I checked the dataset for missing values, duplicate records, and inconsistencies. I then performed the necessary cleaning and preprocessing steps to prepare the data for further analysis.

### 3. Loading Data into PostgreSQL

After preparing the dataset, I connected Python to PostgreSQL and loaded the data into the database.

This allowed me to perform SQL queries on the dataset and answer different business questions related to customer purchases and shopping patterns.

### 4. SQL Analysis

I wrote SQL queries to explore customer behavior and identify useful patterns in the data.

The analysis focused on questions related to customer segments, purchasing habits, customer loyalty, and factors that may influence purchasing decisions.

The SQL queries used for this analysis are available in `customer_behavior_sql_queries.sql`.

### 5. Power BI Dashboard

I connected the PostgreSQL database to Power BI and used the data to create an interactive dashboard.

The dashboard helps present the analysis through visualizations, making it easier to understand customer shopping patterns and identify trends in the dataset.

The Power BI dashboard file is `customer_behavior_dashboard.pbix`.

### 6. Report and Presentation

Finally, I summarized the analysis and its findings in a project report. I also prepared a presentation using Gamma AI to present the key insights and recommendations in a clear format.

## Project Files

Here are the main files included in this repository:

- `Customer_Shopping_Behavior_Analysis.ipynb` — Python notebook containing data import, exploration, cleaning, preprocessing, and database connection code.
- `customer_behavior_sql_queries.sql` — SQL queries used to analyze the customer shopping dataset.
- `customer_behavior_dashboard.pbix` — Power BI dashboard for visualizing the analysis.

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/SumitKumar621/customer-trends-data-analysis.git
cd customer-trends-data-analysis
```

### Step 2: Run the Python Notebook

Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook or JupyterLab.

Install the required Python libraries if they are not already installed:

```bash
pip install pandas numpy sqlalchemy psycopg2-binary jupyter
```

Run the notebook cells to explore, clean, and prepare the dataset.

### Step 3: Set Up PostgreSQL

- Install PostgreSQL and create a database.
- Update the database connection details in the notebook.
- Run the relevant notebook cells to load the processed data into PostgreSQL.

**Note:** Make sure to use your own database credentials rather than sharing them in the repository.

### Step 4: Run the SQL Queries

Open `customer_behavior_sql_queries.sql` in your SQL editor and connect to the database containing the dataset.

Execute the queries to explore customer shopping behavior and answer the business questions.

### Step 5: Open the Power BI Dashboard

Open `customer_behavior_dashboard.pbix` in Power BI Desktop.

If required, update the database connection settings to connect the dashboard to your PostgreSQL database.

## What I Learned

Through this project, I got practical experience with different stages of a data analysis workflow, including:

- Cleaning and preparing data using Python and Pandas.
- Exploring datasets to understand their structure and identify patterns.
- Connecting Python with PostgreSQL and loading data into a database.
- Writing SQL queries to answer business-related questions.
- Building an interactive dashboard in Power BI.
- Presenting analytical findings in a structured and understandable way.

## Conclusion

This project helped me understand how Python, SQL, and Power BI can be used together to analyze customer data. It also gave me an opportunity to practice converting raw data into meaningful insights that can support business decisions.
