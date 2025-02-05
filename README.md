# Retail Analytics Capstone

## Project Overview
This project is my final submission for **MIS581 - Business Intelligence and Data Analytics** at **Colorado State University - Global**. It explores predictive analytics in retail using **SAS Studio** to analyze sales trends, optimize inventory, and evaluate marketing effectiveness. The goal was to find actionable insights that help retailers make better decisions based on data.

## Datasets
I used two datasets from Kaggle, both of which are uploaded in this repository:

1. **[Retail Store Sales Transactions](https://www.kaggle.com/datasets/marian447/retail-store-sales-transactions)** – Contains detailed sales transactions, including date, product categories, quantities sold, and revenue.
2. **[Retail Sales Data with Seasonal Trends and Marketing](https://www.kaggle.com/datasets/abdullah0a/retail-sales-data-with-seasonal-trends-and-marketing)** – Includes sales revenue, units sold, discounts, marketing spend, store ID, and product category to analyze seasonal patterns and marketing effectiveness.

## Project Structure
This repository is structured to make it easy to navigate:

**Retail_Analytics_Capstone/**
Code/ → Contains SAS scripts for data preparation and hypothesis testing

Retail and Warehouse Sales Prep.sas – Prepares the retail sales dataset
Scanner Data Prep.sas – Cleans and formats the scanner dataset
H1 and H2 Code.docx – Code for Hypotheses 1 & 2
H3 Code.docx – Code for Hypothesis 3
H4 Code.docx – Code for Hypothesis 4
Datasets/ → Includes both raw and cleaned datasets

Raw_Data/ – Original files
Retail and warehouse Sales.csv – Processed retail data
scanner_data.csv – Processed scanner dataset
Project_Submissions/ → Final deliverables

Brian_Goff_344580_Mod_7.docx – Full project write-up
Project_Document/ – Additional documentation
Results/ → Output from analysis

H1 and H2 analysis results.pdf
H3 analysis results.pdf
H4 analysis results.pdf
Retail and Warehouse Sales dataset preparation results.pdf
Scanner dataset preparation results.pdf
LICENSE – Project license

README.md – This file

## SAS Studio Workflow
All analysis was done in **SAS Studio**, following these steps:

1. **Upload the Datasets**
   - Load datasets into **WORK.IMPORT** (Retail Sales) and **WORK.IMPORT1** (Scanner Data).

2. **Prepare the Data**
   - Run `Retail and Warehouse Sales Prep.sas` and `Scanner Data Prep.sas` to clean and structure the data.

3. **Run Hypothesis Testing**
   - `H1 and H2 Code.docx` – Examines marketing campaigns and seasonal trends
   - `H3 Code.docx` – Looks at the effect of store location on sales
   - `H4 Code.docx` – Identifies consistently high-performing products

4. **Analyze the Results**
   - All statistical outputs are stored in the `Results/` folder.

## Analysis & Findings
The full analysis, methodology, and insights are available in the **Final Research Paper (Project_Submissions/Brian_Goff_344580_Mod_7.docx)**. The project also includes a **PowerPoint presentation** and **Oral Presentation Video** covering the findings.

The key areas of focus were:
- Identifying seasonal and category-based sales trends
- Measuring the impact of marketing campaigns
- Evaluating store location influence on sales
- Finding high-performing product categories

## How to Use This Repository
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/Retail_Analytics_Capstone.git
