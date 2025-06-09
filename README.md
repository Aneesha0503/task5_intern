# task5_intern
# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) project using the famous Titanic dataset. The goal of this project is to extract meaningful insights about passenger survival by leveraging statistical summaries and visual exploration techniques.

##

##  Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

##  Files

* `train.csv` - Titanic training dataset
* `Titanic eda.ipynb` - Jupyter Notebook containing full analysis and visualizations
* task5 screenshots intern`.pdf` - PDF version of the notebook with observations

##  Process Followed

1. **Data Loading and Inspection**

   * Used `.head()`, `.info()`, `.describe()` to understand data structure
   * Checked for missing values and class distributions

2. **Univariate Analysis**

   * Plotted histograms and boxplots for numerical features
   * Created countplots for categorical features like `Sex`, `Pclass`, `Survived`

3. **Bivariate Analysis**

   * Analyzed survival rates by `Sex`, `Pclass`, and `Age`
   * Boxplots and countplots used to compare survival distributions

4. **Correlation Analysis**

   * Generated heatmap of numeric correlations
   * Used pairplot to observe feature interactions

##  Key Insights

* **Females had significantly higher survival rates** compared to males.
* **1st class passengers** had better chances of survival than 2nd or 3rd class.
* Passengers who paid **higher fares** were more likely to survive.
* The **age** of survivors tended to be lower on average.
* The dataset had missing values in `Age`, `Cabin`, and `Embarked` which required attention.
