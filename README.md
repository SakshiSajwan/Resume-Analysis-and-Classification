🤖 Resume Analysis & Classification for Recruitment Strategy
This repository contains the complete solution for the Veridia Internship Task, focusing on transforming unstructured resume data into actionable business intelligence for optimizing recruitment and operational decision-making.

Project Goal
To analyze a dataset of 2,484 diverse professional resumes to derive key insights on talent supply and skill demand, and to build a predictive model for automating the initial resume screening process.

🛠️ Tech Stack & Methodology
Languages: Python (3.x)

Libraries: Pandas, NLTK, Scikit-learn, Matplotlib, Seaborn

Key Techniques:

Data Cleaning: URL/Special Character removal, Stopword filtering.

Feature Engineering: TF-IDF Vectorization with tuned N-grams.

EDA: Category Distribution Analysis, Word Cloud Generation.

Modeling: Optimized Linear Support Vector Classifier (LinearSVC).

📊 Key Findings & Results
Feature	Insight	Business Value
Top 15 Skills	Identified statistically critical skills (e.g., machine learning, sql database) using TF-IDF scoring.	Direct input for ATS keyword weighting and defining core requirements.
Talent Pool	Analysis of 25 job categories revealed high concentration in entry-level dev roles and scarcity in specialized fields (e.g., Healthcare, Arts).	Defines where to redirect sourcing efforts for a balanced talent pipeline.
Predictive Model	Achieved a final classification accuracy of 72% in assigning resumes to one of 25 job categories.	Provides a tool ready for use as a Departmental Router to accelerate the initial screening and sorting process.

Export to Sheets
🚀 Recommended Next Steps (Veridia)
Implement Departmental Router: The model should be deployed to group resumes into broad functional departments (e.g., IT, HR, Finance) rather than 25 specific titles, maximizing the model's current 72% efficiency for speedier initial routing.

Optimize ATS: Integrate the Top 15 TF-IDF skills directly into the Applicant Tracking System's ranking criteria.

📂 Repository Structure
File/Folder	Description
Resume_Analysis.ipynb	Primary Deliverable: The complete Jupyter Notebook with all data cleaning, EDA, visualization, and ML modeling steps.
Resume.csv	The raw dataset used for analysis.
Report_Document.pdf	The final business report summarizing findings and recommendations.

Data Source & Availability:
The primary dataset used for this analysis (Resume.csv) is not included in this repository due to its large size (approx. 66 MB, mainly due to the unstructured text columns).

The original dataset can be downloaded from the source:
Kaggle Resume Dataset
