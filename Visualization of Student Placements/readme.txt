About Dataset

Edit
This dataset contains exam scores and grant statuses of students who applied for Erasmus program at a university. Data can be used to analyze performance of students from different faculties and departments, or to create a model that determines whether a student from a faculty with a certain score can receive a grant.

VARIABLES
INDEX: Unique index number of each record.
COUNTRIES: Countries to be attended under Erasmus programme
UNIVERSITIES: Universities to be attended under the Erasmus programme
FACULTIES: Faculties where the students are enrolled
DEPARTMENTS: Departments where the students are enrolled
EXAM SCORE: Students' Erasmus exam scores
GRANT: Column indicating whether the students received a grant (1: received, 0: not received)
Note:
Each faculty has own quota. This means that a student scoring 80 in a faculty may not receive a grant, while a student scoring 80 in another faculty may receive grant. This should be taken into account as it may affect model you create.

Usage:
This dataset can be used for various analyses, such as:

Performance comparisons between faculties/departments.
Analysis of average exam scores by faculties/departments.
Analysis of faculties' quotas and exam scores.
Analysis of universities' quotas and faculty/department data.
Analysis of universities' countries and faculties/departments distributions.
Additionally, with this dataset, models can be created such as to determine whether a student will receive grant based on specified values.

Exam Score and Grant Data of Erasmus Applicants: https://www.kaggle.com/datasets/acareren/exam-and-grant-data-of-erasmus-applicants/data
Grant Prediction Based on Faculty and Exam Scores: https://www.kaggle.com/code/acareren/grant-prediction-based-on-faculty-and-exam-scores

This prediction model was built using logistic regression based faculty x and exam scores.
