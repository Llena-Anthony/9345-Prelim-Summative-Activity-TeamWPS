# 9345 Prelim Summative Activity – Team WPS  
Descriptive Analytics on Gross Regional Domestic Product (GRDP) by Industry

---

## Project Overview

This repository contains the official documentation, datasets, codes, and outputs for the Preliminary Summative Activity in Data Science.

The project focuses on performing descriptive data analytics on the Gross Regional Domestic Product (GRDP) by Industry across Philippine regions. Through systematic data preprocessing, validation, and statistical analysis, the team aims to describe and explain regional economic patterns.

This project follows proper data science workflow standards and emphasizes data quality, transparency, and reproducibility.

---

## Data Source

All datasets were obtained from the:

Philippine Statistics Authority (PSA)  
OpenStat Database – Gross Regional Domestic Product by Industry

The original datasets are preserved to ensure data integrity and verifiability.

---

## Project Objectives

The main objectives of this project are to:

1. Collect GRDP datasets from official PSA sources  
2. Clean and preprocess raw data  
3. Resolve inconsistencies and formatting issues  
4. Validate sector totals and check data reliability  
5. Perform descriptive statistical analysis  
6. Compute measures of correlation  
7. Generate meaningful visualizations  
8. Interpret results in an academic context  
9. Document all processes clearly  
10. Present findings professionally  

---

## Scope and Limitations

### Scope
- Descriptive statistics  
- Exploratory data analysis  
- Correlation analysis  
- Visualization of economic trends  
- Regional and sectoral comparison  

### Limitations
- The study does not include predictive modeling  
- Analysis is limited to available PSA data  
- Results depend on the accuracy of published datasets  
- Some preprocessing decisions involve assumptions  

---

## Methodology

The project follows a structured data science workflow:

### Data Collection
- Downloaded GRDP datasets from PSA website  
- Organized files by region and year  

### Data Preprocessing
- Removed unnecessary symbols and dot prefixes  
- Standardized sector names  
- Converted data types  
- Handled missing values  
- Checked for duplicate entries  
- Resolved double-counting risks  
- Organized main sectors and sub-sectors  

### Data Validation
- Verified totals against sub-sector values  
- Checked consistency across regions  
- Ensured numerical accuracy  
- Cross-checked summary statistics  

### Descriptive Analysis
- Computed mean, median, range, variance, and standard deviation  
- Analyzed sector contributions  
- Compared regional economic structures  

### Correlation Analysis
- Computed Pearson correlation  
- Computed Spearman correlation  
- Interpreted relationships between sectors  

### Visualization
- Created charts and graphs  
- Displayed trends and distributions  
- Summarized patterns visually  

### Interpretation and Reporting
- Explained findings  
- Related results to economic context  
- Documented insights  

---

## Repository Structure

```yaml
data:
  raw:        Original PSA datasets
  processed:  Cleaned datasets for analysis

notebooks:    Google Colab notebooks for Descriptive Analytics

src:          Python scripts for preprocessing and analysis

docs:         Methodology and documentation

reports:      Figures and written summaries

README.md:        Project overview
.gitignore:       Ignored files
requirements.txt: Python dependencies
```

---

## Tools and Technologies

The following tools were used:

- Python  
- Google Colab Notebook  
- Microsoft Excel  
- Google Sheets  
- Pandas  
- NumPy  
- Matplotlib  
- GitHub  

---

## How to Run the Project

### Requirements

Make sure Python is installed, then install dependencies:

```
pip install -r requirements.txt
```

### Running the Analysis

1. Open Jupyter Notebook  
2. Navigate to the `notebooks` folder  
3. Run the notebooks in sequence  

---

## Team Organization

This project is developed by Team WPS.

| Name |
|------|
| Anthony Llena |
| Nathaniel De La Rosa |
| Adrian Jay Soralde |
| Leo Delos Reyes |
| Lester Aranca |
| Quelvin Ross Dahilan |
| Rabelais Mar Bernabe |
| Randy Jr. Martin |

---

## Project Timeline

| Phase | Description | Period |
|-------|-------------|--------|
| Planning | Task allocation and setup | Week 1 |
| Collection | Data gathering | Week 1 |
| Preprocessing | Cleaning and validation | Week 2 |
| Analysis | Statistical analysis | Week 2 |
| Reporting | Documentation and presentation | Week 3 |

---

## Expected Outputs

- Cleaned GRDP dataset  
- Statistical summary tables  
- Correlation matrices  
- Visual charts  
- Written analysis report  
- Presentation slides  

---

## Academic Integrity

All data sources are properly cited.  
All analyses are original and performed by the team.  
This repository is intended solely for academic purposes.  

---

## Contact Information

Team Leader: Anthony Llena  
Contact Informatio: 2235774@slu.edu.ph
Institution: Saint Louis University (SLU)  
Academic Term: Preliminary Term  

---

## Acknowledgments

The team acknowledges the Philippine Statistics Authority for providing open-access economic data and the course instructor for guidance throughout this project.
