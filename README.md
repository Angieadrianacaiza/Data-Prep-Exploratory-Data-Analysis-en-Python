# Data-Prep-Exploratory-Data-Analysis-en-Python
The Jupyter Notebook at [section06_exploring_data_solution.ipynb](https://github.com/Angieadrianacaiza/Data-Prep-Exploratory-Data-Analysis-en-Python/blob/main/section06_exploring_data_solution.ipynb) focuses on analyzing country-level happiness scores. Here’s a summary of the notebook:

### 1. **Objective**
   - The goal is to help the marketing team share insights about the five happiest countries of the 2010s.
   - Two key tasks:
     1. Create a list of each country’s **highest happiness score**.
     2. Create a list of each country’s **average happiness score**.

### 2. **Data Exploration**
   - The dataset is read using Pandas.
   - There are **2089 rows** and **6 columns** in the `happiness_survey_data.csv` file, including:
     - `country_name`, `year`, `happiness_score`, and others (`social_support`, `freedom_to_make_life_choices`, etc.).
   - Data ranges from 2005 to 2021, with happiness scores spanning between 2 and 8.

### 3. **Data Filtering**
   - Data is filtered for the years **2010 to 2019** for analysis.

### 4. **Analysis**
   - Maximum happiness score for each country:
     - Data is grouped by `country_name`, and the maximum scores are calculated.
   - Average happiness score for each country:
     - Data is grouped similarly to compute average scores.
   - The results are sorted to identify the top five happiest countries based on both measures.

### 5. **Findings**
   - **Top 5 countries based on maximum happiness scores**:
     1. Finland: 7.858
     2. Denmark: 7.788
     3. Switzerland: 7.776
     4. Norway: 7.678
     5. Canada: 7.650
   - **Top 5 countries based on average happiness scores**:
     1. Denmark: 7.618
     2. Switzerland: 7.568
     3. Finland: 7.553
     4. Norway: 7.541
     5. Iceland: 7.518

### 6. **Comparison**
   - The happiest countries lists are consistent for most part, but minor rankings change between highest and average happiness scores.

---

The notebook uses Pandas for data transformation and presents insights about happiness data effectively.
