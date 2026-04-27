## Microbial-Contamination-Analysis
## .Excel . Power bi
End-to-end analysis of microbial contamination in kitchen surfaces, from laboratory sample processing to interactive dashboard visualization.

## 📚 Table of Contents

- [📊 Project Overview](#-project-overview)
- [🛠️ Tools & Technologies](#-tools--technologies)
- [🧪 Dataset Description](#-dataset-description)
- [🔄 Data Cleaning Process](#-data-cleaning-process-excel)
- [🧾 Sample Overview](#-sample-overview)
- [📈 Dashboard Features](#-dashboard-features-power-bi)
- [🔍 Key Insights](#-key-insights)
- [📸 Dashboard Overview](#-dashboard-overview)
- [💡 Recommendations](#-recommendations)
- [📌 Project Type](#-project-type)
- [🙌 Author](#-author)
- [📂 Data Source](#-data-source)
  
## 📊 Project Overview
Kitchen Surface Microbial and Resistance Analysis is a project that explores microbial contamination across different kitchen surfaces and examines antibiotic resistance patterns of isolated organisms.
This project was carried out end-to-end, starting from:
Sample collection from kitchen environments
Laboratory analysis and microbial isolation
Data recording and structuring
Data cleaning and preparation in Excel
Data visualization and dashboard development in Power BI
The aim is to combine microbiological techniques with data analytics to uncover contamination trends, identify dominant microorganisms, and evaluate hygiene practices such as cleaning frequency.

## 🛠️ Tools & Technologies
Microsoft Excel (Data cleaning & preparation)
Power BI (Data visualization & dashboard creation)

## 🧪 Dataset Description
The dataset was generated from laboratory analysis of swab samples collected from different kitchen surfaces.
The dataset includes:
Kitchen_ID
Swab_ID
Surface_Area
Location_Type
Microbe_Type (Bacteria / Fungi)
Organism
Media used (EMB, SDA, etc.)
CFU/ml (Colony Forming Units per ml)
Dilution_factor
Antibiotics
Zone_mm (Zone of inhibition)
Resistance (Susceptible / Resistant)
Cleaning_frequency

## 🔄 Data Cleaning Process (Excel)
Standardized column names and formats
Removed inconsistencies and blank values
Ensured proper numeric formatting for CFU/ml and zone measurements
Structured categorical variables for analysis
Verified data consistency across all kitchen samples

 ## 🧾 Sample Overview
Below is a snapshot of the cleaned dataset:

| Kitchen_ID | Swab_ID | Surface_Area  | Microbe_Type | Organism           | CFU/ml  | Antibiotic | Resistance  | Cleaning_Frequency |
|------------|--------|---------------|--------------|--------------------|---------|------------|-------------|-------------------|
| Kitchen 1  | Swab 1 | Cutting Board | Bacteria     | Proteus mirabilis  | 8.8E+03 | AZ         | Susceptible | Daily            |
| Kitchen 1  | Swab 2 | Table Top     | Fungi        | Aspergillus flavus | 1.1E+03 | -          | -           | Weekly           |
| Kitchen 1  | Swab 3 | Drain         | Bacteria     | Klebsiella spp     | 3.6E+03 | CN         | Susceptible | Daily            |
| Kitchen 1  | Swab 4 | Faucet        | Fungi        | Aspergillus niger  | 2.2E+03 | -          | -           | Weekly           |

## 📈 Dashboard Features (Power BI)
The Power BI dashboard provides interactive insights into:
Total and average CFU/ml
Microbial distribution across surfaces
Antibiotic resistance vs susceptibility patterns
Count of organisms identified
Zone of inhibition by organism and antibiotic
Effect of cleaning frequency on microbial load

## 🔍 Key Insights
Cutting boards and sink areas showed higher microbial loads compared to other surfaces
Proteus mirabilis and Klebsiella spp were among the most frequently isolated bacteria
Fungal organisms such as Aspergillus spp were also present across multiple surfaces
Some isolates showed resistance to antibiotics like LEV and AM
Kitchens cleaned daily generally recorded lower contamination levels than those cleaned weekly

## 📸 Dashboard Overview
<img width="995" height="561" alt="Microbiology Data" src="https://github.com/user-attachments/assets/e7f1aa93-050f-4ae7-af6a-b23a7d1d6f1d" />


## 💡 Recommendations
Based on the analysis:
Increase cleaning frequency of high-contact surfaces like cutting boards and sink areas
Implement stricter hygiene protocols in areas with consistently high CFU levels

Monitor and regulate antibiotic usage to reduce resistance development
Encourage routine microbial surveillance in shared kitchen environments
Improve cleaning methods (not just frequency) to ensure effective microbial reduction

## 🙌 Author
**Okpala Joy Amarachi**  
- GitHub:  https://github.com/amarachiokpala53-del
- LinkedIn: https://www.linkedin.com/in/amarachi-joy-38517b388?utm_source=share_via&utm_content=profile&utm_medium=member_android

## 📂 Data Source
This dataset was generated from laboratory analysis conducted as part of a microbiology research project.  
All samples were collected, processed, and analyzed by the author.

https://github.com/amarachiokpala53-del/Microbial-Contamination-Analysis/blob/main/Microbiology%20Data.xlsx
https://github.com/amarachiokpala53-del/Microbial-Contamination-Analysis/blob/main/Microbiology%20Data.pbix

