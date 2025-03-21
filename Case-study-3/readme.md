# Data Description
The dataset pertains to the Titanic disaster, where the information of passengers aboard the Titanic is recorded. The dataset consists of 891 records and 12 columns, which include:

- *PassengerId*: Unique ID assigned to each passenger.
- *Survived*: Indicates whether the passenger survived (1) or not (0).
- *Pclass*: Passenger class (1st, 2nd, 3rd).
- *Name*: Name of the passenger.
- *Sex*: Gender of the passenger (male/female).
- *Age*: Age of the passenger.
- *SibSp*: Number of siblings/spouses aboard.
- *Parch*: Number of parents/children aboard.
- *Ticket*: Ticket number.
- *Fare*: Fare amount paid by the passenger.
- *Cabin*: Cabin number (if available).
- *Embarked*: Port where the passenger embarked (C = Cherbourg, Q = Queenstown, S = Southampton).

# Overview of the Jupyter Notebook
The notebook includes various analyses and visualizations of the Titanic dataset, including:

## Data Preprocessing
- *Load Dataset*: Loaded train.csv into a DataFrame.
- *Display Data*: Displayed the first few rows of the dataset.
- *Check Data Types*: Verified column data types using info().
- *Check Missing Values*: Checked for any missing values.
- *Handle Missing Values*: Imputed missing values:
  - Age: Filled using mean value.
  - Embarked: Filled with the most frequent value.
  - Dropped Cabin due to excessive missing data.
- *Convert Data Types*: Converted categorical columns to numerical using encoding.

## Data Cleaning & Summary Statistics
- *Drop Unnecessary Columns*: Dropped columns such as Ticket and Cabin for simplicity.
- *Check for Duplicates*: Identified and removed duplicate records.
- *Summary Statistics*: Generated descriptive statistics for numerical columns.

# Data Analysis & Visualizations
The notebook includes various visualizations to better understand the dataset:
- *Survival Rate by Gender*: Bar plot to visualize survival based on gender.
- *Passenger Class Distribution*: Pie chart depicting the distribution of passenger classes.
- *Age Distribution of Passengers*: Histogram showcasing the distribution of passengers' ages.
- *Survival Rate by Passenger Class*: Bar plot comparing survival rates across different passenger classes.
- *Fare Distribution*: Box plot to visualize the distribution of fares paid by passengers.
- *Embarkation Port Distribution*: Pie chart to visualize where most passengers embarked.

# Data Insights
Key observations from the analysis include:

- *Gender and Survival*: Females had a higher survival rate compared to males.
- *Class and Survival*: Passengers in 1st class had a higher survival rate compared to 2nd and 3rd class.
- *Fare Influence*: Higher fares were often associated with higher survival rates.
- *Embarkation Point Impact*: Majority of passengers embarked from Southampton, with varying survival rates.

# Conclusion
The analysis of the Titanic dataset provides key insights into survival factors such as gender, class, and fare amount. The preprocessing, cleaning, and visualization steps ensure an accurate understanding of passenger data and survival outcomes.