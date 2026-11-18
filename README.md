👥 User Behavior Analysis Using Python

📌 Project Overview

A Python-based data analysis project that collects user data from the DummyJSON REST API, processes and cleans the dataset, and performs Exploratory Data Analysis (EDA).

The project explores user demographics, geographical distribution, and statistical relationships through data analysis and visualization.

📁 Project Structure

📦 user-analysis/
│
├── read.py                  # API data extraction
├── main.py                  # Data cleaning & analysis
├── analysis.ipynb           # Jupyter Notebook
├── users.csv                # Extracted dataset
├── README.md
│
└── plots/
    ├── plot1_age_distribution.png
    ├── plot2_avg_age_by_gender.png
    ├── plot3_gender_pie.png
    ├── plot4_top10_cities.png
    ├── plot5_age_vs_height.png
    ├── plot6_age_vs_weight.png
    └── plot7_correlation_heatmap.png

🛠️ Technologies Used

Python

Requests

Pandas

Seaborn

Matplotlib

Jupyter Notebook

⚙️ Project Workflow

1. Data Extraction

Collected user data using the DummyJSON REST API.

Used HTTP GET requests to retrieve data.

Implemented pagination to fetch all available records.

Converted JSON responses into Pandas DataFrames.

Exported the collected data to CSV.

2. Data Exploration

Examined dataset structure and dimensions.

Checked missing values and duplicate records.

Reviewed data types and descriptive statistics.

Explored categorical variables.

3. Data Cleaning

Extracted city and country from nested address data.

Handled missing numerical values using median imputation.

Prepared the dataset for analysis.

4. Exploratory Data Analysis (EDA)

Calculated average user age.

Compared average age by gender.

Analyzed user distribution by gender.

Identified the top 10 cities by user count.

Calculated average height and weight.

Investigated correlations between age, height, and weight.

📊 Analysis Questions

#

Business Question

Analysis

1

What is the average age of users?

Average Age

2

How does average age vary by gender?

Gender Comparison

3

How are users distributed by gender?

Gender Distribution

4

Which cities have the most users?

Top 10 Cities

5

What are the average height and weight?

Statistical Analysis

6

Is there a relationship between age, height, and weight?

Correlation Analysis

📈 Visualizations

1. Age Distribution
2. Average Age by Gender
3. User Distribution by Gender
4. Top 10 Cities
5. Age vs Height
6. Age vs Weight
7. Correlation Heatmap


🎯 Skills & Learning Outcomes

REST API Integration

HTTP Requests & JSON Handling

Data Extraction & Pagination

Data Cleaning & Transformation

Exploratory Data Analysis (EDA)

Statistical Analysis & Correlation

Data Visualization

⚙️ Installation & Usage

# Install dependencies
pip install requests pandas seaborn matplotlib

# Extract data from the API
python read.py

# Run the analysis
python main.py
