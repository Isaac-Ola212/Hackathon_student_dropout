# Factors Influencing Student Dropout

**Student Dropout Analysis** This project looks at factors influencing student dropout rates in secondary education. It includes demographic information, academic performance, and social conditions that may contribute to a student's likelihood of dropping out.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* This dataset was taken from Kaggle and contains anonymised personal information. https://www.kaggle.com/datasets/meharshanali/student-dropout-prediction-dataset

## Business Requirements

* BR1: Student Performances
• Examine the correlation between attendance rate, daily study hours, scholarship status, and GPA.
• Evaluate whether students receiving scholarships demonstrate higher academic performance.
• Present data relationships using appropriate visualizations such as scatter plots (study hours per day vs. GPA) and heat maps (correlation matrix).Financial

* BR2: Student’s wellness
•Analyse and compare stress index, travel time minutes, part time job, attendance rate
•Visualisations such as boxplots and bar charts comparing stress index across student groups (those with/without part-time jobs)
•Enable stakeholders (wellness tutors) to access the data to monitor a student’s wellbeing over time

* BR3: Student Biographical Profiling
•Access to biographical and personal data such as age, gender, family income, parental education
•Analyse should highlight demographic clusters that may benefit from targeted interventions.
•Enable stakeholders (government employees) to have access to biographical and socioeconomic data to target outreach programs to specific student demographics.

* BR4: Predict player model
•Develop a machine learning model to predict the likelihood of a student dropping out.
•This should include academic, behavioural and biographical information to predict the dropout prediction per student.
•Classification?

*  BR5: Interactive Dashboard & Data Exploration
•Develop a user-friendly dashboard specifically designed for non-technical stakeholders. This dashboard should allow users to easily explore and interact with student data, making important insights accessible regardless of technical background.
•Incorporate filtering and segmentation features that enable users to view and categorize data based on various criteria, such as age and gender. These capabilities help stakeholders focus on specific student groups and tailor their analyses accordingly
• For technical users, provide dedicated storytelling pages and advanced analytical tools. These should offer deeper narratives and support drill-down capabilities, allowing for more detailed exploration and understanding of the underlying data patterns.

## Hypothesis and how to validate?
* Hypothesis 1 – Attendance Rate and Dropout
H₀: There is no relationship between attendance rate and student dropout.
H₁: There is a relationship between attendance rate and student dropout.
Test: Pearson Correlation
In the context of the dataset: The analysis will examine whether students with lower attendance rates are more likely to drop out.

* Hypothesis 2 – Gender and Dropout
H₀: There is no significant difference in dropout rates between male and female students.
H₁: There is a significant difference in dropout rates between male and female students.
Test: Independent t-test
In the context of the dataset: The analysis will compare dropout rates between male and female students to determine if gender is associated with student dropout.

* Hypothesis 3 – Scholarship Status and Dropout
H₀: Scholarship status and dropout are independent.
H₁: Scholarship status and dropout are associated.
Test: Chi-Square Test
In the context of the dataset: The analysis will examine whether students with a scholarship are less likely to drop out compared to those without a scholarship.

* The use of visulation tools like Matplotlib and Seaborn was used to show the factors impacting student dropout rates. Additionally, PowerBI was used to create an interactive dashboard.

## Project Plan
* Data collection and set up: Data was taken from Kaggle and saved as CSV file. This data was loaded in VS code.
* Data cleaning: The data extraction, transformation and loading (ETL) was completed. The data was reveiwed for duplicates, outliers, missing values. The data cleaning was completed (processed data folder) analysis was commenced.
* Data analysis and visualisation was completed using XXXXX. The data was presented using XXXXX
* The kanban board link is https://github.com/users/Isaac-Ola212/projects/8
* The interactive dashbaord page was created using PowerBI  


## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* The data was sourced from Kaggle, a Google-owened online platform offering datasets, and tools to learn, practice, and collaborate on real-world data challanges.
* The data does include personal informatipon so needs to be handled carefully and used soley for the purpose of this data analysis. The data was handled using transparent data practices.
* Data hadling was in accordance with GDPR and ethical guidelines.

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Co-Pilot was used for code. 
* Gaps in coding knowledge and AI assistance was helpful.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 


## Main Data Analysis Libraries
* I used the following libraries for data analysis: pandas, scipy.stats, numpy, matplotlib and seaborn.


## Credits 

* Kaggle was the source of the raw data. 
* The use of Co-Pilot helped in generating code and providing explanations. Additionally, support was provided when required by Code Institute course monitor (Vasi) 


## Acknowledgements 
* Thank you to the Hackathon team Isaac Ola, Lena Anwar, Priya Natt, Forhad Ahmed and also Vasi for all the help during the project.
