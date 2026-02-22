# FUTURE_ML_03

Resume Screening System using NLP
🚀 Project Overview

This project is an AI-powered Resume Screening System that automatically analyzes and ranks resumes based on a given job description. It uses Natural Language Processing (NLP) techniques like TF-IDF and Cosine Similarity to identify the best candidates.

The system also includes skill extraction and scoring, making it more accurate and practical for real-world recruitment.

🎯 Objective

Automate resume screening process

Match candidates with job descriptions

Rank candidates based on relevance

Reduce manual hiring effort

🛠️ Tech Stack

Python

Pandas

Scikit-learn

NLP (TF-IDF, Cosine Similarity)

Power BI (for dashboard)

📂 Dataset

Source: Resume Dataset (CSV format)

Columns used:

Resume_str → Resume text

Category → Job role

⚙️ Implementation Steps
1. Data Loading

Load dataset using Pandas

Extract resume text from Resume_str

2. Text Processing

Convert text to lowercase

Remove stopwords and noise

3. Feature Extraction

Apply TF-IDF Vectorization

4. Resume Matching

Use Cosine Similarity to compare resumes with job description

5. Skill Extraction

Extract predefined skills from resumes

6. Scoring System

Similarity Score

Skill Match Score

Final Score = Weighted combination

7. Ranking

Sort candidates based on final score

🧠 Model Details
🔹 TF-IDF Vectorizer

Converts text data into numerical vectors based on word importance.

🔹 Cosine Similarity

Measures similarity between resume and job description.

📊 Output

Ranked list of candidates

Skill match percentage

Final score for each candidate

Example:

Category	Score	Skill Score	Final Score
Data Science	0.82	0.75	0.80
IT	0.65	0.50	0.60
📈 Insights

Most candidates partially match job requirements

Top candidates have strong skill alignment

System reduces manual screening effort significantly

Skill gaps identified across candidates

💡 Features

Automated resume screening

NLP-based ranking

Skill extraction

Candidate scoring system

Dashboard-ready output

🚀 How to Run
# Install dependencies
pip install pandas scikit-learn

# Run the script
python main.py
📁 Project Structure
Resume-Screening-System/
│
├── data/
│   └── Resume.csv
│
├── main.py
├── ranked_candidates.csv
├── README.md
🔥 Future Improvements

Use spaCy NLP for better parsing

Add Named Entity Recognition (NER)

Build web app using Streamlit

Integrate with real ATS systems

🎯 Business Impact

Saves time in recruitment

Improves hiring accuracy

Reduces human bias

Enables faster decision-making

👩‍💻 Author

Jenifer Shalika S

⭐ Conclusion

This project demonstrates how NLP can be used to automate and optimize the hiring process, making recruitment smarter and more efficient.
