# Startup Funding Dataset Analysis 🚀

## 📋 Overview
This repository contains a comprehensive dataset on **startup funding trends**, sourced from Crunchbase. It provides detailed insights into startups' funding history, market categories, and financial performance, enabling data analysts, researchers, and startup enthusiasts to explore patterns in the entrepreneurial ecosystem.

---

## 🎯 Objective
The goal of this dataset is to:
- Analyze **startup funding patterns** over time.
- Identify key factors that contribute to funding success.
- Understand the influence of categories, markets, and geography on startup growth.

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

## 📂 Folder Structure
- `data/`: Contains the startup funding dataset in CSV format.
- `notebooks/`: Includes Jupyter notebooks for analysis and visualization.
- `README.md`: Documentation for the repository.

---

## 🔍 Key Insights (Examples)
Here are some analyses you can perform using this dataset:
- **Funding Trends**: Analyze total funding over time, segmented by year or quarter.
- **Category Analysis**: Identify which markets receive the most funding.
- **Geographical Insights**: Understand how funding varies across countries, cities, and regions.
- **Round-wise Analysis**: Explore which funding rounds (e.g., Seed, Venture, Series A) dominate in funding amounts.

---

## 💡 Possible Applications
- Research startup success factors and funding strategies.
- Create interactive visualizations to showcase trends in startup funding.

---

## 📚 Requirements
pandas, numpy, matplotlib, seaborn

