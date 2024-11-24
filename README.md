# Startup Funding Dataset Analysis 🚀

## 📋 Overview
This repository contains a comprehensive dataset on **startup funding trends**, sourced from Crunchbase. It provides detailed insights into startups' funding history, market categories, and financial performance, enabling data analysts, researchers, and startup enthusiasts to explore patterns in the entrepreneurial ecosystem.

---

## 🎯 Objectives
1. Analyze the distribution of funding across various **categories**, **markets**, and **regions**.
2. Identify **key factors** that influence funding success, such as funding rounds, funding types, and industry focus.
3. Evaluate **geographical trends** to determine the top regions and countries for startup investments.
4. Uncover insights for startups to optimize their funding strategies and for investors to target high-growth sectors.

---

## 📊 Dataset Description
The dataset consists of **54,294 rows** and **39 columns** with detailed information about startups, their funding sources, and business status. Below is a brief description of each column:

| **Column Name**         | **Description**                                                                 |
|--------------------------|---------------------------------------------------------------------------------|
| `permalink`             | Static hyperlink for the startup on Crunchbase.                                 |
| `name`                  | Name of the startup.                                                           |
| `homepage_url`          | Website address of the startup.                                                |
| `category_list`         | Categories that the startup falls under.                                       |
| `market`                | Market the startup caters to.                                                  |
| `funding_total_usd`     | Total funding received (in USD).                                               |
| `status`                | Current operating status (e.g., operational, acquired, shut down).             |
| `country_code`          | Country of origin.                                                             |
| `state_code`            | State of origin.                                                               |
| `region`                | Region of origin.                                                              |
| `city`                  | City of origin.                                                                |
| `funding_rounds`        | Total number of funding rounds.                                                |
| `founded_at`            | Date the startup was founded.                                                  |
| `founded_month`         | Month the startup was founded.                                                 |
| `founded_quarter`       | Quarter the startup was founded.                                               |
| `founded_year`          | Year the startup was founded.                                                  |
| `first_funding_at`      | Date of the first funding received.                                             |
| `last_funding_at`       | Date of the most recent funding received.                                       |
| `seed`                  | Funding received during the seed stage (in USD).                               |
| `venture`               | Venture funding received (in USD).                                             |
| `equity_crowdfunding`   | Funding received by diluting equity.                                            |
| `undisclosed`           | Other undisclosed funding sources.                                             |
| `convertible_note`      | Funding received from convertible notes.                                       |
| `debt_financing`        | Funding received through debts.                                                |
| `angel`                 | Funding received from angel investors.                                         |
| `grant`                 | Funding received from grants.                                                  |
| `private_equity`        | Funding received from private equity investors.                                |
| `post_ipo_equity`       | Funding from equity dilution after IPO.                                        |
| `post_ipo_debt`         | Funding from debts after IPO.                                                  |
| `secondary_market`      | Funding from secondary markets.                                                |
| `product_crowdfunding`  | Funding received through product crowdfunding.                                 |
| `round_A`               | Round A funding received.                                                      |
| `round_B`               | Round B funding received.                                                      |
| `round_C`               | Round C funding received.                                                      |
| `round_D`               | Round D funding received.                                                      |
| `round_E`               | Round E funding received.                                                      |
| `round_F`               | Round F funding received.                                                      |
| `round_G`               | Round G funding received.                                                      |
| `round_H`               | Round H funding received.                                                      |

---

## 🔧 Key Skills and Tools
This project highlights the following **skills** and tools:
- **Programming Languages**: Python  
- **Libraries**:
  - **Pandas**: For data cleaning, wrangling, and analysis.
  - **NumPy**: For numerical computations.
  - **Matplotlib & Seaborn**: For data visualization.
  - **Plotly**: For interactive visualizations.
- **Techniques**:
  - Exploratory Data Analysis (EDA)
  - Feature Engineering
  - Data Visualization
  - Trend Analysis
  - Insight Generation

---

## 📊 Steps Performed
1. **Data Cleaning**:
   - Removed duplicates, handled missing values, and normalized funding amounts.
   - Standardized categorical data for better analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed funding trends across years, quarters, and months.
   - Investigated funding by **categories**, **markets**, and **geographies**.
   - Visualized correlations between funding amounts and variables like `funding_rounds` and `market`.

3. **Geographical Analysis**:
   - Identified top countries, regions, and cities with the highest funding activity.
   - Visualized global funding patterns using heatmaps and bar charts.

4. **Insights Generation**:
   - Determined which markets receive the most funding.
   - Evaluated funding trends across different rounds, such as `seed`, `venture`, and `private equity`.

---

## 📈 Key Insights
Here are some highlights of the analysis:
- **Funding Rounds**: Venture funding accounts for the largest share of investments, followed by private equity.
- **Geographical Trends**:
  - The **United States** leads in total funding, followed by **China** and **India**.
  - Key cities for funding include **San Francisco**, **New York**, and **Beijing**.
- **Market Analysis**:
  - Industries like **Biotechnology**, **Mobile**, **Healthcare**, and **Clean Technology** attract the highest funding.
  - Niche markets, such as **Natural Gas** and **Custom Retail**, receive fewer investments but higher average funding per company.




