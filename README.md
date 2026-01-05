# Heart Disease Risk Factors Analysis

**Codecademy Bootcamp - Applied Data Science with Python**

Statistical analysis investigating cardiovascular risk factors using clinical data from the Cleveland Clinic Foundation.

## 🎯 Project Overview

This project examines whether patients diagnosed with heart disease exhibit significantly elevated cholesterol levels and fasting blood sugar compared to clinical thresholds and population baselines. The analysis uses hypothesis testing and effect size calculations to draw meaningful clinical insights from the data.

### Key Research Questions
1. **Cholesterol Analysis**: Do patients with heart disease have mean cholesterol levels significantly higher than 240 mg/dl?
2. **Fasting Blood Sugar**: Is the prevalence of elevated fasting blood sugar (>120 mg/dl) in this clinical sample significantly higher than the 1988 U.S. national average of 8%?
3. **Comparative Analysis**: How do cardiovascular metrics differ between patients with and without heart disease?

## 📊 Dataset Information
- **Total Patients**: 303
- **Variables**: 9 clinical measurements including age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, maximum heart rate, exercise-induced angina, and ST depression
- **Outcome**: Heart disease presence/absence (binary classification)
- **Source**: UCI Machine Learning Repository (Cleveland Clinic Foundation)

## 🔬 Statistical Methods

This analysis employs rigorous statistical testing:
- **One-sample t-tests** for threshold comparisons
- **Two-sample t-tests** for group comparisons
- **Binomial test** for proportion analysis
- **Effect size calculations** (Cohen's d)
- **Assumption checking** (normality, equal variance)
- **Significance level**: α = 0.05

## 🛠️ Technologies Used
- **Python 3.13**
- **Libraries**: 
  - pandas (data manipulation)
  - numpy (numerical computing)
  - scipy (statistical tests)
  - matplotlib & seaborn (data visualization)
  - statsmodels (advanced statistical analysis)

## 📁 Project Structure
```
heart-disease-risk-analysis/
├── HeartDiseaseResearch_BootCampProject.ipynb  # Main analysis notebook
├── heart_disease.csv                            # Patient clinical data
├── BlairBateman_CodecademyPresentation.pdf      # Project presentation slides
├── requirements.txt                             # Python dependencies
├── .gitignore                                   # Git ignore rules
└── README.md                                    # Project documentation (this file)
```

## 🚀 Getting Started

### Prerequisites
Ensure you have Python 3.8+ installed. Then install required packages:

```bash
pip install -r requirements.txt
```

Or install packages individually:
```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels jupyter
```

### Running the Analysis
1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/heart-disease-risk-analysis.git
   cd heart-disease-risk-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook HeartDiseaseResearch_BootCampProject.ipynb
   ```

4. **Run all cells sequentially** to reproduce the analysis

## 📊 Visualizations

The project includes comprehensive data visualizations:
- Distribution plots comparing groups
- Statistical test result summaries
- Effect size interpretations
- Clinical significance assessments

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- **Statistical hypothesis testing** (t-tests, binomial tests)
- **Effect size calculation and interpretation**
- **Data cleaning and exploratory data analysis**
- **Python data science ecosystem** (pandas, scipy, matplotlib)
- **Scientific communication** and documentation
- **Reproducible research practices**

## 👤 Author

**Blair Bateman**
- **Location**: Olds, Alberta, Canada
- **Role**: Agricultural Researcher & Data Analyst
- **GitHub**: [@blair-agtech](https://github.com/blair-agtech)
- **LinkedIn**: [linkedin.com/in/blairbateman](https://linkedin.com/in/blairbateman)
- **Project**: Codecademy Applied Data Science with Python Bootcamp - January 2026

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

### Data Collection Credits
Special thanks to the principal investigators responsible for data collection:
- **Hungarian Institute of Cardiology**, Budapest: Andras Janosi, M.D.
- **University Hospital**, Zurich, Switzerland: William Steinbrunn, M.D.
- **University Hospital**, Basel, Switzerland: Matthias Pfisterer, M.D.
- **V.A. Medical Center**, Long Beach and **Cleveland Clinic Foundation**: Robert Detrano, M.D., Ph.D.

### Data Source
Dataset obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

### Educational Program
Completed as part of Codecademy's **Applied Data Science with Python Bootcamp**

## 📚 References

1. UCI Machine Learning Repository - Heart Disease Dataset
2. Cleveland Clinic Foundation Clinical Database
3. Codecademy

## 🔄 Future Improvements

Potential extensions of this analysis:
- Machine learning classification models (logistic regression, random forest)
- Feature importance analysis


---

**Note**: This is an educational project completed as part of a data science bootcamp. Results are for demonstration purposes and should not be used for medical decision-making.

*Last Updated: January 2026*

