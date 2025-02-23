
![thought-catalog-505eectW54k-unsplash](https://github.com/user-attachments/assets/a3dce493-7725-4eb6-a03f-cb5af788c2da)

# Casptone-Three---Optimizing-Candidate-Selection---Hector-Sanchez

# 📌 **Optimizing Candidate Selection Using Recruitment Data**

## 📖 **Introduction**

**Problem Statement**

Hiring and operations managers often struggle to find high-quality candidates. Many hiring decisions are made out of desperation due to staffing issues, which can negatively impact business performance. This project aims to develop a predictive model that can identify the most hireable candidates, helping managers streamline their recruitment process and focus on high-potential applicants.

**Project Objective**

✔️ Build a predictive model that classifies whether a candidate is likely to be hired.

✔️ Perform data preprocessing, feature engineering, and model evaluation.

✔️ Identify the best-performing model through hyperparameter tuning and evaluation metrics.

## 📊 **Dataset Overview**

**Dataset Name:** Recruitment Data DatasetAuthor: Rabie El Kharoua (Synthetic dataset for educational purposes)

**Key Features:**

Demographics: Age, Gender, DistanceFromCompany

Qualifications: EducationLevel, SkillScore, PersonalityScore, InterviewScore

Experience: ExperienceYears, PreviousCompaniesWorked

Target Variable: HiringDecision (1 = Hired, 0 = Not Hired)

**Feature Breakdown:**

Feature -->  Description

Age -->  Candidate's age

Gender -->  Male (0), Female (1)

EducationLevel -->  0 = No Formal Education, 1 = Bachelor's Type 1, 2 = Bachelor's Type 2, 3 = Master's, 4 = PhD

ExperienceYears -->  Years of work experience

PreviousCompaniesWorked -->  Number of companies a candidate worked at previously

DistanceFromCompany -->  Distance (in miles) from the company

InterviewScore, SkillScore, PersonalityScore -->  Evaluation scores (0-100)

RecruitmentStrategy -->  0 = Undefined, 1 = Aggressive, 2 = Moderate, 3 = Conservative

HiringDecision -->  Target variable (0 = No, 1 = Yes)

## 🛠 **Data Processing & Feature Engineering:**

✅ Missing Values: No missing values in the dataset.

✅ Feature Mapping: Converted Gender and EducationLevel into human-readable labels.

✅ One-Hot Encoding: Applied to RecruitmentStrategy.

✅ Feature Scaling: Standardized numerical features (Age, InterviewScore).

## 📈 **Exploratory Data Analysis (EDA):**

🔍 **Key Insights**

Positive Correlation with Hiring: Candidates with higher Interview, Personality, and Skill Scores had a greater chance of being hired.

Aggressive Recruitment Strategy led to higher hiring rates.

Education Level Impact: Candidates with a Master’s degree or PhD were more likely to be hired, while Bachelor’s Type 1 candidates had the lowest hiring rate.

Distance from Company had little impact on hiring decisions.

## 📊 **Visualizations**

✔️ Histograms for Age, ExperienceYears, PreviousCompaniesWorked, InterviewScore, SkillScore, and PersonalityScore.

✔️ Bar Plots for categorical features (Gender, EducationLevel, RecruitmentStrategy).

✔️ Correlation Heatmap to analyze relationships between features.

✔️ Box Plots to examine feature relationships with HiringDecision.

## 🚀 **Model Development**

**Machine Learning Approach:**

Built and compared multiple models to predict hiring decisions.

Performed hyperparameter tuning to optimize model performance.

Evaluated models based on accuracy, precision, recall, and F1-score.

**Best Performing Model**

🔹 Model Selected: ✅ Best Random Forest 

🔹 Key Metrics:✔️ Accuracy: 92.3%  ✔️ Precision: 88.7%  ✔️ Recall: 83.5%  ✔️ F1-score: 86.1%

## 🎯 **Conclusion & Next Steps**

📌 **Key Takeaways:**

Candidates with higher interview, skill, and personality scores have a greater chance of being hired.

Aggressive recruitment strategies yield higher hiring rates.

Educational background plays a role in hiring decisions, with a preference for Master’s and PhD candidates.

📌 **Future Work:**

Expand dataset to include real-world recruitment data.

Implement deep learning models for enhanced accuracy.

Incorporate a Cost Analysis of hiring decisions.

💡 **How to Use This Project**

1️⃣ Clone this repository:

git clone https://github.com/https://github.com/hesanche94.git

2️⃣ Install dependencies:

pip install -r requirements.txt

3️⃣ Run the model:

python train_model.py

# 📬 **Connect with Me:**

💼 LinkedIn: www.linkedin.com/in/hechector-sanchez-skaggs

📧 Email: h.sanche94@gmail.com

📂 Portfolio: https://github.com/hesanche94

⭐ **If you found this project helpful, please consider giving it a star on GitHub!** ⭐
