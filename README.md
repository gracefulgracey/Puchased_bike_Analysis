# Puchased_bike_Analysis
![](bike_image.jpg)![](bike_image.jpg)![](bike_image.jpg)
## **INTRODUCTION**
#### This project aims to analyze the various socioeconomic and demographic factors that affect bike purchasing behavior, using a dataset that includes detailed information on individuals' income, education, occupation, home and car ownership, commute distance, region, age, gender, marital status, and the number of children.
## **OBJECTIVES**
### The primary objectives of this project are:
- To identify key factors that influence the decision to purchase a bike.
- To analyze the relationship between income levels and bike purchasing behavior.
- To examine how education and occupation impact the likelihood of buying a bike.
- To explore the role of demographic variables such as age, gender, and marital status in bike purchase decisions.
- To investigate regional differences in bike purchasing patterns.
- To assess the influence of home and car ownership on the decision to buy a bike.
- To determine the impact of commute distance on bike purchase decisions.
## DATA SOURCE 
#### The data used for the analysis of bike sales was collected through a survey conducted using a Google Form. The survey gathered responses from a diverse group of participants, providing detailed information on various demographics and socio-economic factors. 
## TOOLS USED
#### For the "Analysis of Bike Sales" project, the following tools will be utilized:
#### Excel for Data Cleansing and Transformation
Excel will be used as the primary tool for data cleansing and transformation. This involves:
- **Data Import:** Importing the raw data from the survey into Excel.
- **Data Cleaning:** Identifying and correcting any inaccuracies or inconsistencies in the data. This includes handling missing values, removing duplicates, and ensuring uniform formatting.
- **Data Transformation:** Structuring the data for analysis. This includes creating new calculated columns, such as categorizing income ranges, calculating age groups, and summarizing key metrics.
- **Data Validation:** Ensuring that the data is accurate and reliable through validation techniques and checks.
#### Power BI for Analysis and Visualization
Power BI will be used to perform the analysis and create visualizations for the dataset. This involves:
- **Data Import:** Importing the cleansed and transformed data from Excel into Power BI.
- **Analysis:** Using Power BI's analytical tools to uncover insights, identify trends, and perform statistical analysis. This includes creating measures, calculated columns, and utilizing DAX functions for advanced calculations.
- **Visualization:** Designing interactive and dynamic visualizations such as charts, graphs, and dashboards to present the findings. This includes visualizations to depict the relationship between bike purchases and various factors like income, age, occupation, and region.
- **Reporting:** Generating comprehensive reports that summarize the key insights and findings from the analysis. These reports can be shared and accessed interactively by stakeholders.
## DATA CLEANSING AND TRANSFORMATION
#### Data Cleansing Steps:
#### Marital Status:
- Standardization: Ensured that marital statuses were consistently labeled and changed as either M to "Married" or S to "Single".
#### Gender:
- Standardization: Ensured that gender entries were consistently changed as  M for "Male" and F for "Female".
- Correction of Inconsistencies: Corrected any inconsistent entries or misspellings in the gender column.
#### Age:
- Categorization: Added an "Age Range" column to categorize respondents into “Children” (under 31), "Youth" (under 50) and "Adult" (50 and over) using the IF function.
#### Duplicates:
- Identification: Checked for duplicate entries based on the unique identifier (ID) and other relevant attributes.
- Removal: Removed any duplicate entries to ensure each respondent was only represented once in the dataset.
#### Error Checking:
- Validation of Data Entries: Ensured that all numerical fields (e.g., Income, Children, Cars) contained valid numerical values.
- Correction of Errors: Addressed any errors found in the data entries, such as incorrect income formats or invalid ages.
