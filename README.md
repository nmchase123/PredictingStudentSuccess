# Predicting Student Success

Hi! This is a project where I explored student performance data to predict whether students will pass their final year. I wanted to see how different factors—like study habits, family background, and extracurricular activities—impact student success.  

---

## What I Did

- I used the **UCI Student Performance dataset**, which includes information about students’ demographics, family, school life, and grades.  
- I cleaned and transformed the data:
  - Converted categorical features into numbers  
  - One-hot encoded columns like parents’ jobs and reasons for choosing a school  
  - Turned the final grade (`G3`) into a **pass/fail target**  
- I implemented a **Perceptron model from scratch** to classify students as passing or failing.  
- Split the data into training and testing sets and tracked how the model learned over time.  

---

## Skills & Tools

- **Python:** pandas, numpy  
- **Data Visualization:** seaborn, matplotlib  
- **Machine Learning:** Perceptron classifier, train-test split, accuracy evaluation  
- **Data Sources:** UCI Machine Learning Repository (`ucimlrepo` package)  

---

## What I Found

- My Perceptron model achieved **88% accuracy** on the test set!  
- Visualizations helped me understand the distribution of grades and differences across genders and other features.  

---

## How to Use

1. Clone the repo:  
```bash
git clone https://github.com/nmchase123/PredictingStudentSuccess.git
