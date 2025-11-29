# claims-analysis2

### Overview
- This project simulates the type of analysis performed daily by healthcare data analysts, medical billing specialists, and health informaticians. Understanding claims data is essential for revenue cycle management, coding accuracy audits, payer contract analysis, clinical quality reporting, and healthcare operations optimization.

##
### Data sources
- STONYBRK_20240531_CODE
- STONYBRK_20240531_HEADER
- STONYBRK_20240531_LINE

##

### Run Notebook
1. Open Google Colab
2. Upload the CSV files
3. Run all cells sequentially

##

### Summary 
- The distribution of claims among payers is not consistent. The majority of all claims are made by the top five payers, suggesting a strong reliance on particular insurance partners.
- Recurring clinical presentations and service patterns are highlighted by the most common ICD-10 codes and CPT/HCPCS procedures that show regularly across numerous claims.
-The bulk of claims are made up by a limited number of providers. A disproportionately high percentage of all claims are made by the top five billing providers combined.

##

### Required Libraries 
- pandas
- numpy
- matplotlib