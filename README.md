# College-Placement-Trend-Analysis

# Project Overview

This project delves into a comprehensive analysis of college student placement data to uncover key factors influencing placement success. Leveraging a rich dataset, this study aims to identify correlations between various student attributes and their placement outcomes, providing actionable insights for educational institutions, career counselors, and students themselves.

# Dataset

The analysis is based on the *college_student_placement_dataset.csv*  file. This dataset comprises 10,000 entries and 10 distinct features for each student.

# Data Dictionary

The dataset includes the following columns:

- College_ID: Unique identifier for each college.
- IQ: Intelligence Quotient score of the student.
- Prev_Sem_Result: Result of the previous semester (likely on a scale of 1-10 or similar).
- CGPA: Cumulative Grade Point Average.
- Academic_Performance: A score reflecting overall academic performance (scale 1-10).
- Internship_Experience: Indicates whether the student has internship experience (Yes/No).
- Extra_Curricular_Score: Score for participation in extracurricular activities (scale 0-10).
- Communication_Skills: Score representing communication abilities (scale 1-10).
- Projects_Completed: Number of projects completed by the student.
- Placement: The target variable, indicating if the student secured a placement (Yes/No).

# Data Analysis Process

The analysis process involved:
1. **Exploratory Data Analysis (EDA)**: Initial examination of the dataset to understand its structure, statistical summaries (mean, standard deviation, min, max, etc. for numerical columns), and data types.
2. **Conditional Filtering:**
   - Identified students with an IQ score greater than 100.     
   - Analyzed students with an IQ score greater than 100 who also secured placements.
   - Identified students with an IQ score less than 100.
   - Analyzed students who secured placements regardless of other factors.
   - Identified students who did not get any placements.
   - Analyzed students who had internship experience.
   - Analyzed students who had internship experience and secured placements.
   - Identified students who had no internship experience but still secured placements.
   - Analyzed students with a CGPA greater than 5.
   - Identified students with an extracurricular score greater than 5 who secured placements.
   - Identified students with an extracurricular score less than 5 who secured placements.
   - Analyzed students who completed more than 2 projects.
   - Identified students with a CGPA greater than 9, who completed 1 or fewer projects, and secured placements.
3. **Statistical Analysis:**
4. **Data Visualization:**

# Key Findings and Insights:
- **IQ and Placement:** Students with higher IQ scores tend to have a higher chance of placement. The average IQ of placed students is higher than that of unplaced students.
- **Internship Experience:** While internship experience is a valuable asset, the analysis showed that it does not significantly influence the average IQ of students. Furthermore, a notable number of students secured placements even without prior internship experience.
- **CGPA and Projects:**  A high CGPA is a strong indicator of placement success. Students with CGPA greater than 9 have a good chance of placement, even with a limited number of completed projects (1 or less).
- **Extracurricular Activities:** Extracurricular involvement varies in its impact. Higher scores in extracurricular activities generally correlate with placements, but even students with lower extracurricular scores can achieve placement success.
- **Communication Skills:** Communication skills appear to play a significant role in placement outcomes, as evidenced by the distribution of scores between placed and non-placed students.

# Tools and Technologies:
- Python: Programming language for data analysis.
- Pandas: For data manipulation and analysis.
- NumPy: For numerical operations.
- Matplotlib: For data visualization.
- Seaborn: For enhanced data visualization.

##  Future Work
- Predictive modeling to forecast placement success based on academic history.
- Time-series trend analysis over multiple years of placement data.
- Deployment of interactive dashboards using Power BI or Streamlit.


## How to Run the Project
1. Clone the repository.
2. Ensure you have Python installed (preferably Python 3.x).
3. Install the required libraries using pip.
4. Place the **college_student_placement_dataset.csv** file in the same directory as the Jupyter Notebook.
5. Open and run the **College_Placement_Analysis.ipynb** notebook using Jupyter Notebook or JupyterLab.
   
