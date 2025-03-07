# Iris Dataset Analysis

This project explores the **Iris dataset** using Python. The dataset contains measurements of iris flowers and their species. The goal is to analyze and visualize the data.

## Progress So Far

###  **Task 1: Source the Data Set**
- Imported the **Iris dataset** from `sklearn.datasets`.
- Explained what `load_iris()` returns in simple terms.

###  **Task 2: Explore the Data Structure**
- Printed the **shape** of the dataset.
- Displayed the **first and last 5 rows**.
- Listed the **feature names** and **target classes**.

###  **Task 3: Summarize the Data**
- Calculated **mean, min, max, standard deviation, and median** for each feature.

###  **Task 4: Visualize Features**
- Created **histograms** for each feature using `matplotlib`.
- Added **titles and axis labels** to improve readability.

###  **Task 5: Investigate Relationships**
- Created a **scatter plot** comparing **sepal length** and **petal length**.
- Color-coded the points based on the three different species.

###  **Task 6: Analyze Relationship**
- Used **`numpy.polyfit`** to compute a **regression line** for the scatter plot.
- Plotted the **regression line** on top of the scatter plot.

###  **Task 7: Analyze Class Distributions**
- Created **box plots** to show the distribution of **petal lengths** for each species.
- Compared the spread and median values of petal lengths.

## How to Run the Code

```bash
# Install required libraries
pip install pandas numpy scikit-learn matplotlib

# Run the script
python iris_analysis.py
