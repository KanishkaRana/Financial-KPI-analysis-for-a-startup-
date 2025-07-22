# Financial KPI Analysis for Startup (Blue Tokai Coffee Roasters) ☕📊

This project focuses on a comprehensive financial Key Performance Indicator (KPI) analysis for Blue Tokai Coffee Roasters, a prominent startup. The analysis encompasses data cleaning, in-depth financial and cohort analysis, data visualization, and a final interactive dashboard.

## Project Overview

The primary goal of this project was to understand the financial health and customer behavior of Blue Tokai Coffee Roasters. This involved:

* **Data Cleaning and Initial Analysis (Excel):** 🧹 Preparing the raw financial data for further analysis.
* **Deeper Analysis & Cohort Analysis (Google Colab with Python):** 🔬 Uncovering trends, calculating key financial metrics, and performing cohort analysis to understand customer lifetime value and retention.
* **Data Visualization (Google Colab with Python):** 📈 Creating insightful visualizations to represent the findings.
* **Interactive Dashboard (Power BI):** 🖥️ Developing a user-friendly and interactive dashboard for stakeholders to easily monitor key financial performance indicators.

## Project Structure

* `data/`: Contains the raw and cleaned datasets (e.g., Excel files).
* `notebooks/`: Jupyter notebooks (or `.py` scripts) used in Google Colab for data analysis and visualization.
* `powerbi/`: Power BI project files (`.pbix`) and any related assets.
* `images/`: Screenshots or exports of the Power BI dashboard.
* `README.md`: This file.

## Analysis and Methodologies

### 1. Data Cleaning and Initial Analysis (Excel)

* **Tool:** Microsoft Excel
* **Process:** Handled missing values, removed duplicates, corrected data types, and performed initial sanity checks on the financial data. Basic aggregations and summary statistics were also computed.

### 2. Deeper Analysis & Cohort Analysis (Google Colab with Python)

* **Tool:** Google Colab (Python with libraries like Pandas, NumPy)
* **Key Analyses:**
    * **Financial Metrics:** Calculation of revenue, profit, operating expenses, marketing spend, customer acquisition cost (CAC), lifetime value (LTV), and profit margin.
    * **Cohort Analysis:** Grouped customers by their acquisition date to track their behavior (e.g., spending, retention) over time. This helped in understanding customer lifetime value and identifying trends in customer engagement.

### 3. Data Visualization (Google Colab with Python)

* **Tool:** Google Colab (Python with libraries like Matplotlib, Seaborn, Plotly)
* **Visualizations:** Created various charts and graphs to illustrate financial trends, customer cohorts, and other key insights derived from the data.

### 4. Final Dashboard (Power BI)

* **Tool:** Microsoft Power BI
* **Purpose:** To present the key financial KPIs and insights in an interactive and easily digestible format. The dashboard allows for dynamic filtering and exploration of the data.

## Power BI Dashboard

Below is a snapshot of the interactive Power BI dashboard, showcasing key financial metrics and trends for Blue Tokai Coffee Roasters:

![Blue Tokai Financial Dashboard](btokaimagedash.jpg)

This dashboard provides a quick overview of:
* Sum of Revenue
* Sum of ProfitPerWeek
* Sum of Marketing Spend and Sum of Operating Expense
* Sum of New Customers by Month and Day
* Weekly LTV by Weekly CAC
* Profit Margin %
* Sum of ProfitPerWeek by Year, Quarter, Month and Day
* Sum of Revenue by Year, Quarter, Month and Day
* Sum of Total Customers
* Sum of Weekly CAC
* Sum of Marketing Spend
* Sum of Operating Expense

## How to Run/View the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd financial-kpi-analysis-bluetokai
    ```
2.  **View Power BI Dashboard:**
    * Download and install [Power BI Desktop](https://powerbi.microsoft.com/downloads/).
    * Open `powerbi/BlueTokaidashboardbyKanishka.pbix` in Power BI Desktop to interact with the dashboard.
3.  **Explore Analysis Notebooks:**
    * Open the Jupyter notebooks in the `notebooks/` directory using Google Colab or Jupyter Notebook/Lab to see the data cleaning, analysis, and visualization code.

## Technologies Used

* Microsoft Excel 📝
* Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly) 🐍
* Google Colab ☁️
* Microsoft Power BI 📊

## Contact

For any questions or collaborations, feel free to reach out:
* **LinkedIn:** [www.linkedin.com/in/kanishka-kumari04](https://www.linkedin.com/in/kanishka-kumari04) 🔗
