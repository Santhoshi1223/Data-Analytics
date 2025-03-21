# Data Description
The dataset contains student scores for various questions in an assessment. It comprises *86 records and 12 columns* with details of scores for each question and the total marks obtained by the student.

### Columns Description:
- *Total:* Total marks obtained by the student.
- *Q1aM4:* Marks scored in part (a) of Question 1 (out of 4).
- *Q1bM6:* Marks scored in part (b) of Question 1 (out of 6).
- *Q2aM6:* Marks scored in part (a) of Question 2 (out of 6).
- *Q2bM4:* Marks scored in part (b) of Question 2 (out of 4).
- *Q3aM5:* Marks scored in part (a) of Question 3 (out of 5).
- *Q3bM5:* Marks scored in part (b) of Question 3 (out of 5).
- *Q4aM3:* Marks scored in part (a) of Question 4 (out of 3).
- *Q4bM7:* Marks scored in part (b) of Question 4 (out of 7).
- *Q5M10:* Marks scored in Question 5 (out of 10).
- *Q6aM4:* Marks scored in part (a) of Question 6 (out of 4).
- *Q6bM6:* Marks scored in part (b) of Question 6 (out of 6).

---

# Overview of the Jupyter Notebook
The notebook contains a detailed analysis of the dataset, including:

- *Initial Data Exploration:*
  - Checking for null values and data types.
  - Viewing the first few rows of the dataset.
  
- *Summary Statistics:*
  - Calculation of mean, median, and standard deviation for each question.
  
- *Visualizations:*
  - Distribution of total marks using histograms.
  - Box plots for identifying outliers in question-wise marks.
  - Correlation heatmap to analyze relationships between marks scored in different questions.
  - Bar plots for question-wise average marks.
  
---

# Data Insights
Key findings from the analysis include:

- *Question-Wise Performance:* Some questions show higher average scores, while others have significant variability.
- *Correlation Patterns:* Positive correlation between scores in related parts of the same question.
- *Missing Values:* Several records contain missing marks for specific questions.
- *Outliers and Score Distribution:* Some outliers exist in total marks and individual questions, indicating irregularities in scoring patterns.
- *Total Score Analysis:* A wide range of total scores with noticeable variations between students.