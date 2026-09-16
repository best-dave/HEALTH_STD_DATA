# 🧬 STD Cases Data Analysis

## Project Overview
This project analyzes reported sexually transmitted disease (STD) cases using Python.
The analysis explores disease distribution, state-level differences, demographic patterns, population context, and changes in reported cases over time.
The project demonstrates how data analysis techniques can be applied to public health data to identify patterns and communicate findings effectively.

## 🎯 Project Objectives
The main objectives of this project were to:
* Examine the distribution of reported STD cases by disease.
* Compare reported cases across states.
* Analyze trends in reported cases over time.
* Explore STD cases across different age groups and genders.
* Examine the relationship between reported cases and population.
* Analyze population-based case rates where the required population data were available.
* Identify patterns that may be useful for public health data analysis.

## 🛠️ Tools & Technologies
* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**

## 📊 Dataset
The dataset contains STD-related records across multiple diseases, states, years, genders, and age groups.

### Main Variables
* Disease
* Disease Code
* State
* Year
* Gender
* Age
* Age Code
* STD Cases
* Population
* Cases per 100K

The dataset covers a multi-year period, allowing trends in reported cases to be explored over time.

## 🔎 Analysis Process
The analysis followed a structured workflow:
1. Imported the dataset into Python.
2. Examined the dataset structure and variables.
3. Checked for missing values.
4. Investigated disease and demographic categories.
5. Compared reported cases across diseases and states.
6. Examined changes in reported cases over time.
7. Explored population and case relationships.
8. Examined population-based rates where appropriate.
9. Created visualizations to communicate the results.
10. Interpreted the observed patterns.

## 🔍 Key Findings
The analysis revealed several important patterns:
* **Disease distribution:** Reported cases were not evenly distributed across the diseases included in the dataset.
* **State-level variation:** Reported STD cases differed across states, demonstrating variation in the distribution of reported cases.
* **Population context:** States with larger populations can naturally have higher raw case counts, making population-based measures useful when comparing locations.
* **Time trends:** Reported STD cases changed across the study period, allowing temporal patterns to be examined.
* **Age groups:** The frequency of reported cases varied across age groups, providing useful information for demographic analysis.
* **Missing data:** Some records contained missing population or rate information. These missing values were considered carefully rather than automatically treating missing population values as zero.
* **Data interpretation:** Raw case counts and population-based rates provide different perspectives and should be interpreted according to the analytical question.

The findings describe patterns in the available data and should not be interpreted as evidence of causation.

## 📈 Visualizations
The project contains visualizations examining:
* Percentage distribution by disease
* STD cases compared with population
* States with the highest reported case counts
* Total STD cases by disease
* Trends in reported STD cases over time

The visualizations are available within the Jupyter Notebook and as image files in the repository.

## 📁 Repository Contents
* `health_STD_cases.ipynb` — Jupyter Notebook containing the analysis.
* `STD Cases.csv` — Dataset used for the analysis.
* PNG files — Visualizations generated during the analysis.

## 💡 Skills Demonstrated
* Data cleaning
* Missing-value identification
* Exploratory Data Analysis (EDA)
* Descriptive statistics
* Grouping and aggregation
* Trend analysis
* Population-based analysis
* Rate analysis
* Data visualization
* Python
* Pandas
* NumPy
* Matplotlib
* Public health data analysis

## 📝 Conclusion
This project demonstrates the application of Python-based data analysis techniques to public health data.
By examining disease distribution, geographic variation, demographic characteristics, population context, and time trends, the project shows how structured analysis can turn raw health records into meaningful and interpretable insights.
This project forms part of my data analytics portfolio and demonstrates my ability to work with health datasets, perform exploratory analysis, handle missing information, and communicate findings using visualizations.
