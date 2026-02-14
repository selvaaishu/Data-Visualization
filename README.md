Interactive Sales Dashboard
📌 Project Overview

The Interactive Sales Dashboard is a data visualization project designed to analyze and present sales performance using statistical and interactive visualizations.

This dashboard provides insights into:

📈 Sales trends over time

🌍 Regional sales performance

📦 Product-wise sales analysis

💰 Price distribution and outliers

🔎 Correlation between numerical variables

The goal of this project is to demonstrate mastery in:

Seaborn statistical visualizations

Plotly interactive dashboards

Professional layout design

Data analysis and interpretation

🛠️ Technologies Used

Python

Pandas

Seaborn

Matplotlib

Plotly

📂 Dataset Information

File: sales_data.csv

Columns:

Date

Product

Quantity

Price

Customer

Region

Total_Sales

The dataset contains sales transaction data used to generate insights and visualizations.

📊 Visualizations Included

This dashboard contains at least 5 different chart types:

📈 Line Chart – Sales Trend Over Time

📊 Bar Chart – Sales by Region

📦 Box Plot – Price Distribution by Product

🎻 Violin Plot – Quantity Distribution

🔥 Correlation Heatmap – Numerical Relationships

📊 Scatter Plot – Price vs Quantity

🎨 Dashboard Features

2×2 Professional Layout using Plotly Subplots

Interactive Hover Effects

Zoom and Pan Functionality

Clean Color Theme

Centered Title & Structured Layout

🚀 Setup Instructions
Step 1: Clone the Repository
git clone https://github.com/your-username/Sales-Dashboard.git
cd Sales-Dashboard

Step 2: Install Required Libraries
pip install -r requirements.txt


Or manually install:

pip install pandas seaborn matplotlib plotly

Step 3: Run the Dashboard
python dashboard.py


OR open:

dashboard.ipynb


in Jupyter Notebook.

📊 Dashboard Interpretation Guide
📈 Sales Trend

Shows how total revenue changes over time.
Helps identify growth patterns and seasonal spikes.

🌍 Sales by Region

Compares performance across different regions.
Helps identify high-performing markets.

📦 Price Distribution (Box Plot)

Displays median price, variability, and outliers.
Helps detect premium vs low-cost products.

🎻 Quantity Distribution (Violin Plot)

Shows density and spread of product sales volume.

🔥 Correlation Heatmap

Displays relationships between:

Quantity

Price

Total_Sales

Helps understand how variables influence revenue.

🧠 Technical Implementation Details

Data cleaned using Pandas

Date converted to datetime format

GroupBy operations used for aggregation

Seaborn used for statistical plots

Plotly Subplots used for dashboard layout

Interactive components built with Plotly

🧪 Testing & Validation

Verified total sales calculations

Checked missing values

Validated correlation results

Confirmed dashboard responsiveness

🎯 Learning Outcomes

Through this project, the following skills were developed:

Statistical visualization using Seaborn

Interactive dashboards using Plotly

Multi-plot layout management

Professional data storytelling

Visualization customization and theming
