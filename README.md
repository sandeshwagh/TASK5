# TASK5Step 1: Load the Data

Use pandas.read_csv() or appropriate function to load your dataset.

Example:

import pandas as pd
df = pd.read_csv('your_dataset.csv')



---

Step 2: Initial Exploration

Get a basic understanding of the data:

df.head()
df.info()
df.describe()
df.value_counts()
df.isnull().sum()



---

Step 3: Univariate Analysis

Analyze individual variables:

For numerical columns: histograms, boxplots

For categorical columns: countplots


import seaborn as sns
import matplotlib.pyplot as plt

sns.histplot(df['column_name'])
sns.boxplot(x='column_name', data=df)
sns.countplot(x='categorical_column', data=df)



---

Step 4: Bivariate/Multivariate Analysis

Identify relationships between variables:

sns.pairplot(df)
sns.heatmap(df.corr(), annot=True)
sns.scatterplot(x='feature1', y='feature2', data=df)



---

Step 5: Insights and Observations

After each plot or table, write down key observations.

Example: “Most values in column X are concentrated between A and B.”




---

Step 6: Summarize Findings

Summarize all key trends and insights discovered during the analysis.

Highlight:

Outliers or missing data issues

Correlations

Trends or groupings




---

Step 7: Deliverables

Create a Jupyter Notebook with all code, visualizations, and observations.

Export the notebook as a PDF (via File > Export as PDF) with clean markdown documentation.
