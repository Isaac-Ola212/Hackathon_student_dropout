# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Factors Influencing Student Dropout

## Student Dropout Analysis

This project looks at factors influencing student dropout rates in secondary education. It includes demographic information, academic performance, and social conditions that may contribute to a student's likelihood of dropping out.


## Dataset Content
* This dataset was taken from Kaggle and contains anonymised personal information. https://www.kaggle.com/datasets/meharshanali/student-dropout-prediction-dataset

## Business Requirements

* BR1: Student Performances.  

    - Examine the correlation between attendance rate, daily study hours, scholarship status, and GPA.  
    - Evaluate whether students receiving scholarships demonstrate higher academic performance.  
    - Present data relationships using appropriate visualisations such as scatter plots (study hours per day vs. GPA) and heat maps (correlation matrix).  

* BR2: Student wellness.  

    - Analyse and compare stress index, travel time minutes, part time job, and attendance rate.  
    - Visualisations such as boxplots and bar charts comparing stress index across student groups (those with and without part-time jobs).  
    - Enable stakeholders (wellness tutors) to monitor a student’s wellbeing over time.  

* BR3: Student Biographical Profiling.  

    - Access to biographical and personal data such as age, gender, family income, and parental education.  
    - The analysis should highlight demographic clusters that may benefit from targeted interventions.  
    - Enable stakeholders (government employees) to access biographical and socioeconomic data to support outreach programs.  

* BR4: Predictive model.  
    - Develop a classification model to predict the likelihood of a student dropping out.
    - This includes academic, behavioural, and biographical information to predict dropout per student (0 = retained, 1 = dropout).  

* BR5: Interactive Dashboard & Data Exploration.  
    - Develop a user-friendly dashboard specifically designed for non-technical stakeholders. This dashboard allows users to explore and interact with student data, making insights accessible regardless of technical background.  
    - Incorporate filtering and segmentation features such as age, gender, and scholarship status to support targeted analysis.  
    For technical users, include storytelling pages and drill-down capabilities for deeper data exploration.  

## Hypothesis and how to validate?

Visualisation tools such as Matplotlib and Seaborn were used to show the factors impacting student dropout rates. Additionally, Power BI was used to create an interactive dashboard.

### Hypothesis 1 – Attendance Rate and Dropout  

H₀: There is no relationship between attendance rate and student dropout.  
H₁: There is a relationship between attendance rate and student dropout.  

Test: Pearson Correlation  

In the context of the dataset: The analysis examines whether students with lower attendance rates are more likely to drop out.  

### Hypothesis 2 – Gender and Dropout  

H₀: There is no significant difference in dropout rates between male and female students.  
H₁: There is a significant difference in dropout rates between male and female students.  

Test: Independent t-test  

In the context of the dataset: The analysis compares dropout rates between male and female students to determine if gender is associated with dropout.  

### Hypothesis 3 – Scholarship Status and Dropout  

H₀: Scholarship status and dropout are independent.  
H₁: Scholarship status and dropout are associated.  

Test: Chi-Square Test  

In the context of the dataset: The analysis examines whether students with a scholarship are less likely to drop out compared to those without a scholarship.  



## Project Plan
- Data collection and set up: Data was taken from Kaggle and saved as a CSV file. This data was loaded in VS Code.  

- Data cleaning: The ETL process (extract, transform, load) was completed. The data was reviewed for duplicates, missing values, and inconsistencies. The cleaned dataset was saved in the processed data folder.  

- Data analysis and visualisation: Analysis was completed using Matplotlib and Seaborn. The data was presented using bar charts, boxplots, and heatmaps.  

- The kanban board link is https://github.com/users/Isaac-Ola212/projects/8  

- The interactive dashboard page was created using Power BI  

## The rationale to map the business requirements to the Data Visualisations
The selected data visualisations were designed to directly address the defined business requirements by presenting key patterns, relationships, and trends in student data. Each visual was chosen based on its suitability for communicating specific insights in a clear and interpretable manner.

### BR1: Student Performance  

Visualisations Used: Academic Performance vs Dropout (boxplot), Correlation Heatmap (numeric features)  

Rationale: The boxplot allows comparison of academic performance between students who dropped out and those who did not. The correlation heatmap highlights relationships between variables such as attendance, GPA, and study behaviour.  

### BR2: Student Wellness  

Visualisations Used: Attendance vs Dropout (boxplot)  

Rationale: Attendance is a key indicator of student engagement and wellbeing. The visual highlights differences between dropout and non-dropout groups, supporting early identification of disengaged students.  

### BR3: Student Biographical Profiling  

Visualisations Used: Gender Distribution (countplot), Age Distribution (histplot), Department Analysis (barplot)  

Rationale: These visuals provide insight into the demographic composition of the dataset and help identify groups that may require targeted intervention.  

### BR4: Predictive Model (Dropout Prediction)  

Visualisations Used: Correlation Heatmap, Academic Performance vs Dropout, Attendance vs Dropout  

Rationale: These visuals support feature selection by identifying variables strongly associated with dropout, ensuring the model is based on meaningful predictors.  

### BR5: Interactive Dashboard & Data Exploration  

Visualisations Used: Dropout Distribution (countplot), Scholarship Status vs Dropout (barplot), All charts integrated into dashboard  

Rationale: These visuals provide a clear overview of dropout patterns. Dashboard filters allow users to explore data by gender, age, and scholarship status, supporting both high-level insights and deeper analysis.  

## Analysis techniques used
* Data visualisation tools (Matplotlib and Seaborn) were used to analyse the dataset and identify factors impacting student dropout.  

* Statistical tests such as Pearson correlation, independent t-test, and chi-square test were applied.  

## Ethical considerations
* The data was sourced from Kaggle and contains anonymised personal information.  
* The data was handled responsibly and used only for the purpose of this analysis.  
* Data handling followed GDPR guidelines and ethical data practices.  

## Dashboard Design
* The dashboard was developed using Power BI to support understanding of factors influencing student dropout.  
* It includes charts and filters that allow users to explore data by gender, age, and scholarship status, with drill-down features for deeper analysis.  

## Unfixed Bugs
* Minor issues related to GitHub workflow and environment setup were encountered and resolved during development.  

## Development Roadmap
* Improvements were made in GitHub workflow, debugging, and data analysis processes throughout the project.  
* Support from tutors and tools such as Copilot helped refine the implementation.  

## Main Data Analysis Libraries
* pandas, scipy.stats, numpy, matplotlib, seaborn  

## Credits 
* Kaggle was the source of the raw data.  
* Copilot assisted with code generation and explanations. Support was also provided by the Code Institute course monitor.  

## Acknowledgements 
* Thank you to the Hackathon team Isaac Ola, Lena Anwar, Priya Natt, Forhad Ahmed and Vasi for their support during the project.