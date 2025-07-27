# Cybersecurity Breach Pattern Analysis

This project simulates and analyzes cybersecurity-related activity using synthetic data.  
We use the `Faker` library to generate realistic fake data for users, login attempts, and security alerts.
    
Technologies Used: Python · Pandas · Seaborn · Matplotlib · Faker · Jupyter Notebook
Data Files: `users.csv`, `login_logs.csv`, `alerts.csv`

# Project Structure

This project follows a modular folder structure for clarity and reproducibility:

CyberSecurity_Project/
│
├── data/              # Contains CSV files (users.csv, login_logs.csv, alerts.csv)
├── images/            # Saved charts 
├── notebooks/         # Jupyter notebooks
├── README.md          # Project documentation
└── requirements.txt   # Python dependencies

> The Jupyter notebook resides inside the `notebooks/` folder and loads data from `../data/`.

## Dataset Description (Simulated using Faker)

- **users.csv** – User metadata (ID, department, role, access level)  
- **login_logs.csv** – Login attempt logs (success/failure, timestamps, IPs)  
- **alerts.csv** – System security alerts (types, resolution status)

 ## Key Analyses & Visualizations

1. Line Chart – Daily Failed Login Attempts
2. Horizontal Bar Chart – Top 10 Users with Most Failed Login Attempts
3. Bar Chart – Failed Login Attempts by City
4. Bar Chart – Most Common Security Alert Types
5. Pie Chart – Resolved vs Unresolved Alerts
6. Bar Chart – Alerts by Department
7. Line Chart – Time-Based Trend of Login Failures

## Final Insights

- Certain users and regions show a higher concentration of failed logins  
- Brute-force and suspicious login alerts dominate the alert types  
- Some departments face more frequent alert activity  
- Login failures spike on specific dates, useful for monitoring windows  
- The project simulates a realistic, data-driven approach to breach detection

## How to Run This Project

1. Clone this repo:
   git clone https://github.com/yourusername/Cybersecurity-Data-Analysis.git
   cd Cybersecurity-Data-Analysis
2. Install dependencies:
   pip install -r requirements.txt
3. Open Jupyter Notebook:
   jupyter notebook CyberSecurity_Analysis.ipynb
   
## Skills Demonstrated

1. Data Generation with Faker
2. Exploratory Data Analysis (EDA)
3. Grouping, Filtering, and Merging in Pandas
4. Time Series Analysis
5. Data Visualization with Seaborn & Matplotlib
6. Project Structuring for GitHub

## Acknowledgments

1. Faker for generating realistic data
2. Seaborn and Matplotlib for visualizations

## Disclaimer
This is a simulated project for educational and portfolio purposes. No real security data is used.
