# Student Performance Analysis

Project submitted for the AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 (BharatCares).

## Project Description
This project analyses how factors such as gender, parental education, lunch type and test preparation affect students' exam scores (math, reading, writing). It includes data cleaning, exploratory data analysis (EDA) and a machine learning model that predicts student performance.

## Dataset
- Name: Students Performance in Exams
- Link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams
- Size: 1000 rows, 8 columns (gender, race/ethnicity, parental level of education, lunch, test preparation course, math score, reading score, writing score)

## Technologies Used
- Python 3
- pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn
- Jupyter Notebook

## Setup and Run Instructions
1. Clone the repository:
   ```
   git clone <your-repo-link>
   cd <your-repo-folder>
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Download the dataset from the link above and place the CSV file in the project folder.
4. Launch the notebook:
   ```
   jupyter notebook G_Karthik_Reddy_StudentPerformanceAnalysis.ipynb
   ```
5. Run all cells from top to bottom.

## Key Findings
- Students who completed the test preparation course scored 74.03 on average vs 66.68 for those who did not (a ~7.3 point gap).
- Standard lunch is linked to higher average scores (71.41) than free/reduced lunch (65.18).
- Average score rises with parental education, from 63.84 (some high school) to 78.45 (master's degree).
- Linear Regression was the best-performing model (R² = 0.145) among Linear Regression, Random Forest and Gradient Boosting.

## Project Structure
```
├── G_Karthik_Reddy_StudentPerformanceAnalysis.ipynb
├── requirements.txt
├── README.md
└── G_Karthik_Reddy_ProjectReport.docx
```

## Author
G Karthik Reddy — B.Tech, Artificial Intelligence and Data Science, Chaitanya Bharathi Institute of Technology
