# Chips Category Analytics & Trial Evaluation

## Project Overview
This project analyses customer purchasing behaviour within the chips category and evaluates the effectiveness of a retail store trial using a **trial vs control** methodology. The analysis was completed as part of the **Quantium Data Analytics Job Simulation** and focuses on translating data insights into business recommendations.

The project covers **customer segmentation**, **sales drivers**, and **experimental uplift analysis**, culminating in a **client-ready presentation**.

---

## objectives
- Understand who purchases chips and how purchasing behaviour varies by customer segment  
- Identify key drivers of chip sales, including pack size and customer demographics  
- Evaluate the performance of trial stores by comparing them against matched control stores  
- Communicate insights clearly to support strategic planning decisions  

---

## Dataset Description
The analysis uses three main datasets:
- **Transaction data** – individual purchase records including product details and sales values  
- **Customer data** – customer segmentation information such as lifestage and affluence  
- **Store-level data** – monthly aggregated sales metrics used for trial evaluation  

All data was provided as part of the simulation.

---

## Methodology

### 1. Data Preparation
- Checked for missing values, duplicates, and data type consistency  
- Created additional features such as pack size and monthly time periods  
- Merged transaction and customer datasets for analysis  

### 2. Customer & Category Analysis
- Analysed total sales, customer counts, and purchasing behaviour  
- Identified key customer segments driving chip sales  
- Evaluated pack size performance across the category  

### 3. Trial vs Control Analysis
- Identified trial stores and matched control stores using **pre-trial sales similarity**  
- Split data into **pre-trial** and **trial** periods based on available time coverage  
- Adjusted control store sales to create a fair comparison baseline  
- Measured uplift during the trial period and investigated drivers of change  

### 4. Visualisation & Reporting
- Created visual comparisons of trial vs control store performance  
- Summarised insights using structured storytelling (Pyramid Principle)  
- Delivered findings in a client-ready PDF presentation  

---

## Key Insights
- Older family customer segments contribute the highest share of chip sales  
- Mainstream customers drive volume, while premium customers contribute higher value per purchase  
- Trial stores showed positive divergence from their adjusted control stores during the trial period  
- Sales uplift was primarily driven by increased customer numbers rather than higher purchase frequency  

---

## Tools & Technologies
- **Python** (pandas, numpy, matplotlib)  
- **Jupyter Notebook / Google Colab**  
- **Excel** (chart validation and presentation support)  
- **PowerPoint / PD**
