# Iris_data_analysis

**Introduction**
----------------------------------------------
The Iris dataset is one of the most popular datasets in data science. It contains information about three species of the Iris flower: Iris-setosa, Iris-versicolor, and Iris-virginica. Each entry consists of four features—sepal length, sepal width, petal length, and petal width—measured in centimeters, with 50 samples per species. This EDA will explore these features to discover relationships, patterns, and characteristics that can help differentiate the species.

Dataset Overview
---------------------------------------------
The dataset has 150 samples and 5 columns:

**sepal length (cm)**

**sepal width (cm)**

**petal length (cm)**

**petal width (cm)**

**species (target class: Iris-setosa, Iris-versicolor, Iris-virginica)**

Objectives
-------------------------------------------
The main objectives of this analysis are:

**Understand the distribution** of each feature in the dataset.

**Explore relationships** between the features.

**Visualize patterns** to distinguish between the three Iris species.

**Identify outliers and anomalies** in the data, if any.

**Summarize insights** that could aid in classification tasks.

Analysis Steps
--------------------------------------------
**Data Loading and Preprocessing:**
Load the data and check for missing values or inconsistencies
Perform basic statistical analysis to understand each feature's properties

**Univariate Analysis:**
Analyze each feature individually using visualizations (e.g., histograms, box plots).
Understand the distribution and summary statistics of each feature.

**Multivariate Analysis:**
Explore relationships between features with scatter plots, pair plots, and correlation matrices.
Visualize how the features separate the three species.

**Feature Engineering (Optional):**
Create additional features, if necessary, to enhance the analysis.

**Insights and Summary:**
Summarize key findings and insights from the data analysis.

**Requirements**
-----------------------------------------
To run the analysis, you will need the following Python libraries:

**pandas** - for data manipulation

**numpy** - for numerical operations

**matplotlib and seaborn** - for data visualization

Results and Insights
------------------------------------------

**The following key insights were discovered from the EDA:**

**Feature Distributions**: Each feature shows a distinct distribution. Sepal length and width vary less distinctly between species, whereas petal length and width provide clearer separation.

**Species Differentiation**: Iris-setosa is easily distinguishable from the other two species based on petal measurements, whereas Iris-versicolor and Iris-virginica show more overlap.

**Correlations**: Petal length and petal width have a strong positive correlation, which is helpful in distinguishing species.

DataSource Link 
------------------------------------------
Data Source : https://www.kaggle.com/datasets/uciml/iris
