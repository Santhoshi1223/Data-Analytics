# Data Description
The dataset pertains to the *"Mid-marks"* of students from semester 2, mid-term 1, under the "ALPHA" section. It includes the marks of various subjects for 718 students across 8 columns.

### Dataset Columns:
- *S.No*: Serial number of the student.
- *DV*: Marks scored in Design and Verification.
- *PP*: Marks scored in Programming Practices.
- *FIMS*: Marks scored in Financial Information and Management Systems.
- *FL*: Marks scored in Formal Languages.
- *BEEE*: Marks scored in Basic Electrical and Electronics Engineering.
- *M-II*: Marks scored in Mathematics-II.

---

# Overview of the Jupyter Notebook
The notebook performs various operations to analyze and visualize the dataset, including:

### 1. *Data Exploration:*
- Displaying the first 5 records using df.head().
- Checking the shape of the dataset using df.shape.
- Getting a summary of the dataset with df.info().
- Checking for null values using df.isnull().sum().

---

### 2. *Summary Statistics:*
- Statistical summary using df.describe().
- Analyzing subject-wise distributions and trends.

---

### 3. *Data Visualization:*
The notebook includes several visualizations to explore and analyze the dataset:

- *Bar Plot*: Subject-wise average marks.
- *Box Plot*: Distribution of marks in each subject to identify outliers.
- *Histogram*: Frequency distribution of marks in each subject.
- *Pair Plot*: Visualizing pairwise relationships between numerical columns.
- *Heatmap*: Correlation between different subjects to find relationships.

---

# Data Insights
Key insights derived from the analysis include:

1. *Subject-Wise Performance:* Average marks vary across different subjects, with some subjects showing higher performance trends.
2. *Outliers Detection:* Box plots indicate the presence of outliers in multiple subjects.
3. *Correlation Analysis:* Correlation heatmap shows relationships between different subjects, with some pairs showing positive correlations.
4. *Score Distribution:* Histograms suggest that the majority of the marks lie in a specific range, indicating performance trends.
5. *Comparison Trends:* Pair plots reveal potential relationships between subject marks.