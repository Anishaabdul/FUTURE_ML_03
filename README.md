# Resume Screening & Candidate Ranking System Using NLP
# Project Title

Automated Resume Screening & Candidate Ranking System Using Natural Language Processing

# Problem Statement

Recruiters often receive hundreds of resumes for a single job opening.
Manually reviewing each resume is:

Time-consuming

Inconsistent

Prone to bias

Difficult to scale

This project builds a Machine Learning–based resume screening system that:

Extracts resume content

Compares resumes with job descriptions

Scores candidates based on relevance

Ranks candidates automatically

Identifies missing skills

The system mimics a simplified Applicant Tracking System (ATS).

# Dataset Used

Dataset Source:
Kaggle

Dataset: Resume Dataset

The dataset contains:

Resume text

Job categories

A custom job description was defined for similarity comparison.

# Tools & Technologies

Python

Jupyter Notebook

Pandas

Scikit-learn

TF-IDF Vectorization

Cosine Similarity

Basic NLP preprocessing

# Project Workflow
1️. Resume Text Preprocessing

Lowercasing

Removing punctuation

Removing special characters

Cleaning newline characters

2️. Job Description Parsing

A target job role was defined (e.g., Data Scientist).
The job description was cleaned using the same preprocessing steps.

3️. Feature Extraction

Used TF-IDF (Term Frequency–Inverse Document Frequency) to convert resumes and job description into numerical feature vectors.

4️. Similarity Scoring

Used Cosine Similarity

Measured similarity between each resume and the job description

Generated a similarity score between 0 and 1

Higher score → Better match

5️. Candidate Ranking

Resumes were sorted based on similarity score to generate a ranked shortlist.

6️. Skill Gap Identification

Defined required skills (e.g., Python, Machine Learning, SQL).
System highlights missing skills for each candidate.

# Output Example

For each candidate, the system provides:

Similarity Score

Rank

Missing Skills

# Example:

Candidate	Similarity Score	Missing Skills
Candidate A	0.82	SQL
Candidate B	0.75	Statistics
Candidate C	0.61	Python, ML
# Business Impact

This system helps:

✔ Recruiters shortlist candidates faster
✔ Match resumes to job requirements automatically
✔ Identify skill gaps
✔ Reduce manual resume screening time
✔ Improve hiring efficiency

Instead of reading every resume manually, HR teams can focus only on top-ranked candidates.

# Real-World Applications

Systems like this are used in:

HR-tech startups

Applicant Tracking Systems (ATS)

Recruitment platforms

Enterprise hiring systems

# Future Improvements

Skill weighting (important skills get higher scores)

Named Entity Recognition using spaCy

Resume PDF parsing

Dashboard visualization for HR managers

Multi-job comparison

# Conclusion

This project demonstrates how NLP techniques such as TF-IDF and cosine similarity can transform unstructured resume text into actionable hiring insights.

The system creates a scalable, data-driven hiring support tool that improves recruitment efficiency and decision-making.
