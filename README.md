# FUTURE_ML_03 3️⃣

This is my 3rd task of my internship (Future Interns) where I built a Resume Screening and Candidate Ranking System using Machine Learning and Natural Language Processing (NLP) in Google Colab using Python.

🟢In this project, I worked with real resume data and built a Machine Learning system that can automatically:
1.Screen resumes automatically
2.Match resumes with job descriptions
3.Rank candidates based on job relevance
4.Extract important skills from resumes
5.Identify missing skills
4.Project Work Included

🧑‍💻In this project I have done:
1.Data loading and cleaning
2.Removing unnecessary columns
3.Handling missing values
4.Text preprocessing and cleaning
5.Converting text into numerical format
6.Feature extraction using TF-IDF
7.Resume similarity scoring
8.Candidate ranking system
9.Skill extraction from resumes
10.Missing skill detection

⚙️How the System Works
The system reads resume text and compares it with a job description to determine how well a candidate matches the job role.
📄Resume Score
Each resume receives a similarity score between 0 and 1.
Higher score means better candidate match.

📊Candidate Ranking
Candidates are ranked from highest score to lowest score.
Top candidates are the most suitable for the job role.

🧠Skill Extraction
The system extracts important skills from resumes such as:
Python
Machine Learning
Data Analysis
Pandas
Numpy
SQL
Deep Learning

📉Missing Skills Detection
The system compares candidate skills with required job skills.
Example:
Candidate Skills:Python,Pandas
Missing Skills:Machine Learning,SQL,Deep Learning
⚔️Tools and Technologies Used
Python
Google Colab
Pandas
NLTK
Scikit-learn
TF-IDF Vectorizer
Cosine Similarity
Dataset

📈Dataset used for this project is a Resume Dataset from Kaggle.
Dataset includes:
Resume Text
Candidate Category
Resume Information
The dataset was downloaded in CSV format and used for building the Machine Learning system.
Project Output
The system can analyze resumes and automatically rank candidates.
Example:
Input Resume:Machine Learning Resume Text
Output Score → 0.87
Skills → Python,Machine Learning,Pandas
Missing Skills → SQL,Deep Learning

👾Conclusion
This project shows how Machine Learning can help automate resume screening by automatically analyzing and ranking candidates.
This helps companies:
Reduce manual work
Shortlist candidates faster
Identify best candidates quickly
Detect missing skills easily
