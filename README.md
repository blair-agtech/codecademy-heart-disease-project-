# codecademy-heart-disease-project-
Statistical analysis of heart disease risk factors using Python - Codecademy Data Science Bootcamp project examining cholesterol, fasting blood sugar, and cardiovascular metrics

# Heart Disease Risk Factors Analysis

**Codecademy Bootcamp - Applied Data Science with Python**

Statistical analysis investigating cardiovascular risk factors using clinical data from the Cleveland Clinic Foundation.

## 🎯 Project Overview

This project examines whether patients diagnosed with heart disease exhibit significantly elevated cholesterol levels and fasting blood sugar compared to clinical thresholds and population baselines.

### Key Research Questions
1. Do patients with heart disease have mean cholesterol levels significantly higher than 240 mg/dl?
2. Is the prevalence of elevated fasting blood sugar (>120 mg/dl) in this clinical sample significantly higher than the 1988 U.S. national average of 8%?
3. How do cardiovascular metrics differ between patients with and without heart disease?

## 📊 Dataset Information
- **Total Patients**: 303
- **Variables**: 9 clinical measurements
- **Outcome**: Heart disease presence/absence
- **Source**: UCI Machine Learning Repository (Cleveland Clinic Foundation)

## 🔬 Statistical Methods
- One-sample t-tests for threshold comparisons
- Two-sample t-tests for group comparisons
- Binomial test for proportion analysis
- Effect size calculations (Cohen's d)
- Assumption checking (normality, equal variance)

## 🛠️ Technologies Used
- **Python 3.13**
- **Libraries**: pandas, numpy, scipy, matplotlib, seaborn, statsmodels

## 📁 Project Structure
├── HeartDiseaseResearch_BootCampProject.ipynb # Main analysis notebook
├── heart_disease.csv # Patient data
├── SUMMARY_TABLE_EF_AND_SS.csv # Effect size & statistical significance
├── Codecademy_Poster.jpg # Results visualization
├── BlairBateman-CodecademyPresentation.pdf # Project presentation
└── README.md # Project documentation


## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels

Running the Analysis
Clone this repository

Ensure all CSV files are in the same directory as the notebook

Open HeartDiseaseResearch_BootCampProject.ipynb in Jupyter

Run all cells sequentially

📈 Key Findings
Results from statistical testing:

Maximum heart rate analysis (p < 0.0001, large effect size)

Age comparison between groups (p = 0.001, small effect size)

Fasting blood sugar prevalence significantly higher than baseline (p = 0.0004)

👤 Author
Blair Bateman

GitHub: [@YourGitHubUsername]

LinkedIn: [linkedin.com/in/blairbateman]

Project: Codecademy Applied Data Science with Python Bootcamp

📄 License
This project is licensed under the MIT License.

🙏 Acknowledgments
Data collection credited to:

Hungarian Institute of Cardiology, Budapest: Andras Janosi, M.D.

University Hospital, Zurich: William Steinbrunn, M.D.

University Hospital, Basel: Matthias Pfisterer, M.D.

V.A. Medical Center, Long Beach & Cleveland Clinic: Robert Detrano, M.D., Ph.D.


