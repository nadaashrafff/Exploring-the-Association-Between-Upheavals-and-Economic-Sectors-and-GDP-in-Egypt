# Exploring the Association Between Upheavals and Economic Sectors and GDP in Egypt

## Project Overview

This project is a data analysis study that explores how major political and global upheavals affected Egypt’s Gross Domestic Product (GDP) and different economic sectors.

The analysis focuses on three major events:

- The 2011 Egyptian Revolution
- The 2013 Egyptian Revolution
- The 2020 COVID-19 Pandemic

The goal of the project is to understand whether these upheavals had a statistically significant relationship with changes in Egypt’s GDP and sector-level economic performance.

---

## Research Question

Did significant political or global upheavals affect various economic sectors and GDP in Egypt?

---

## Hypothesis

### Null Hypothesis (H₀)

There is no association between the occurrence of major upheavals and variations in Egypt’s Gross Domestic Product (GDP).

### Alternative Hypothesis (H₁)

There is an association between the occurrence of major upheavals and variations in Egypt’s Gross Domestic Product (GDP).

---

## Dataset

The dataset used in this project is:

**Gross Domestic Product by Economic Activity**

The data includes GDP contributions across multiple Egyptian economic sectors, including:

- Agriculture, Forestry, and Fishing
- Petroleum and Gas
- Manufacturing Industries
- Construction
- Transportation and Storage
- Communication and Information
- Suez Canal
- Wholesale and Retail Trade
- Accommodation and Food Services
- Education
- Health
- Other Services
- Total GDP

---

## Methodology

The analysis followed these main steps:

1. **Data Collection**  
   Data was collected from official GDP-by-economic-activity records.

2. **Data Cleaning**  
   The dataset was cleaned by handling missing values and removing or treating outliers where necessary.

3. **Exploratory Data Analysis**  
   Sector-wise trends were analyzed across different years to observe changes before, during, and after major upheavals.

4. **Data Visualization**  
   Several visualizations were created to show GDP trends, sector performance, sector correlations, and period-based comparisons.

5. **Hypothesis Testing**  
   A chi-squared test was used to test whether there is a statistically significant association between upheaval periods and GDP variations.

---

## Key Findings

- The chi-squared test produced a statistically significant p-value of: 5.5794647180362105e-05
- Since the p-value is less than 0.05, the null hypothesis was rejected.
- This suggests that there is a statistically significant association between major upheavals and changes in Egypt’s GDP.
- Some sectors, such as tourism and accommodation, were strongly affected by political instability and the COVID-19 pandemic.
- The Suez Canal sector showed different behavior because it is highly connected to global trade rather than only local political conditions.
- Sectors such as education, health, and social services showed strong correlations, likely due to shared public-sector and policy-related influences.


## Tools and Libraries Used

The analysis was implemented using Python and common data analysis libraries:

Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy

## Repository Contents
.
├── Final Poster DA.pdf
├── Final Power Point DA.pptx
├── Final Report DA.docx
├── Gross Domestic Product.csv
├── Python Notebook Final.ipynb
└── README.md

## File Descriptions
Final Poster DA.pdf
- Final project poster summarizing the research question, methodology, results, and conclusion.
Final Power Point DA.pptx
- Final presentation slides used to present the project.
Final Report DA.docx
- Full written report explaining the project background, methodology, sector analysis, hypothesis testing, results, and conclusion.
Gross Domestic Product.csv
- Dataset used for the analysis.
Python Notebook Final.ipynb
- Python notebook containing the data cleaning, visualization, correlation analysis, and hypothesis testing code.

## How to Run the Notebook
Clone the repository:
git clone https://github.com/nadaashrafff/Exploring-the-Association-Between-Upheavals-and-Economic-Sectors-and-GDP-in-Egypt.git
Open the project folder:
cd Exploring-the-Association-Between-Upheavals-and-Economic-Sectors-and-GDP-in-Egypt
Open the Jupyter Notebook:
jupyter notebook "Python Notebook Final.ipynb"
Make sure the dataset file is in the same folder:
Gross Domestic Product.csv
Run the notebook cells in order.

## Conclusion

This project found evidence of a statistically significant association between major upheavals and changes in Egypt’s GDP. The results show that political and global disruptions can affect economic sectors differently depending on each sector’s exposure to local instability, global trade, public policy, and consumer demand.

The study highlights the importance of using data analysis and visualization to understand how economic sectors respond to major national and global events.

## Team Members
Nada Ashraf
Aly Zaki
Manar Yussri
Ahmed Waleed
Omar Bayoumi

## Supervisor

Dr. Mohamed Taher

## Course Information

Egypt University of Informatics
Computer and Information Systems
Data Analysis Course
