
# Student Performance Analysis – PROEX Winning Project

This project explores how student background, academic behavior, and social factors influence academic performance. Developed for the **PROEX Analytics Competition**.

---

## Competition Context

- **Event**: PROEX – Student Analytics Competition  
- **Team Name**: *Analytics Avengers*  
- **Placement**:  **1st Place**

---

##  Project Objective

To identify the key drivers of academic success by analyzing:
- Family background (e.g., parental education, location)
- Academic behavior (e.g., attendance, preparation)
- Social factors (e.g., gaming time, job status)

---

##  Datasets Used

### 1. **Student-Parent Dataset**
- **Source**: Portuguese Secondary Education
- **Sample Size**: 1,044 students
- **Key Features**:
  - Parental education & occupation
  - Urban vs. rural address
  - Final grade (G3) as the outcome

### 2. **Academic-Social Dataset** (Kaggle)
- **Sample Size**: 493 students
- **Key Features**:
  - Academic scores (HSC, SSC, English)
  - Study habits (attendance, preparation time)
  - Social/behavioral traits (gaming, job, income)

---

##  Methodology

All analysis was performed in **Python using Jupyter Notebooks**, following a reproducible pipeline:

- **Data Cleaning**: No missing values; consistent formats
- **Preprocessing**:
  - Binary encoding for gender, job status, guardian type
  - Scaling of categorical ranges (e.g., income, time)
- **Analysis Techniques**:
  - **Linear regression** using Scikit-learn
  - **Feature comparison and ranking**
  - **Cross-dataset comparison**
  - Visualizations: Boxplots, bar charts, trendlines with Seaborn/Matplotlib

---

## Key Findings

### 1️⃣ Background Factors
- **Urban students** outperform rural (impact score: **+0.896**)
- **Mother’s education** has a stronger positive influence (**+0.472**) than father’s
- **Male students** tend to perform worse (impact: **-0.524** in first dataset)

### 2️⃣ Academic vs Social Behavior
- **Attendance** is the most powerful positive predictor (**+1.594**)
- **Preparation time** and **HSC scores** also contribute positively
- **Gaming time** (**-0.190**) and **having a job** (**-0.220**) are significant negative influences

### 3️⃣ Cross-Context Patterns
- **Gender gap** is consistent: female students outperform males in both datasets
- **Parental education** is a better predictor than income (which had a negligible impact)
- **Location** mattered more in the traditional dataset than in the academic-social one


![image](https://github.com/user-attachments/assets/b3796672-0e0d-495e-b39e-09f04014bca0)


![image](https://github.com/user-attachments/assets/beb3dec8-b63b-4515-a42e-2bf4fabf08a1)


![image](https://github.com/user-attachments/assets/fab64a59-10e9-4740-b868-d1863e365d61)

---

##  Recommendations

- Encourage parental involvement and target support for rural students
- Promote regular **attendance** and structured **preparation routines**
- Educate students and families on the academic impact of **gaming** and **part-time work**
- Focus less on income-based interventions, and more on **education-based support**

---

## Tools & Technologies

- **Jupyter Notebook** (Python environment)
- **Pandas**, **NumPy** for data manipulation
- **Scikit-learn** for regression modeling
- **Matplotlib**, **Seaborn** for visualizations


