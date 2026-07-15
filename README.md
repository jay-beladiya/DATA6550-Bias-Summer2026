# Exploring Data Bias in the Adult Census Income Dataset

## DATA 6550 Summer 2026

### Team Members

* Tirth Laheri
* Jay Beladiya

---

## Project Overview

The purpose of this project is to explore different forms of bias present in the Adult Census Income Dataset. Using exploratory data analysis, visualizations, and statistical testing, we investigated how demographic and socioeconomic factors relate to income and how these patterns could influence the fairness of machine learning models.

Rather than focusing on model development, this project emphasizes understanding the data itself, identifying potential sources of bias, and discussing the ethical implications of using biased datasets in real-world applications.

---

## Project Objectives

* Explore the Adult Census Income Dataset
* Identify known and potential sources of bias
* Perform exploratory data analysis
* Create meaningful visualizations
* Validate observations using statistical tests
* Discuss ethical concerns related to biased datasets

---

## Dataset

**Dataset Name**

Adult Census Income Dataset

**Source**

UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/2/adult

The dataset contains demographic, educational, and employment information collected from the 1994 U.S. Census and is commonly used for fairness and machine learning research.

---

## Repository Structure

```text
DATA6550-Bias-Summer2026
│
├── Analysis
│   ├── Tirth_Laheri_Analysis.ipynb
│   └── Jay_Beladiya_Analysis.ipynb
│
├── Weekly Discussions
│   ├── Discussion - 1.md
│   └── Discussion - 2.md
│
├── Report/
│   └── Final_Report.docx
│
├── data
│   ├── adult.data
│   ├── adult.test
│   ├── adult.names
│   ├── old.adult.names
│   └── Index
│
└── README.md
```

---

## Individual Contributions

### Tirth Laheri

* Data preprocessing and cleaning
* Exploratory data analysis
* Education bias analysis
* Native country representation analysis
* Workclass analysis
* Work hours analysis
* Correlation analysis
* Statistical testing including Chi Square Test, ANOVA, and Cramer's V
* Documentation and notebook preparation

### Jay Beladiya

* Dataset exploration
* Gender and race bias analysis
* Historical bias discussion
* Fairness analysis
* Additional visualizations
* Documentation and project review

---

## Key Findings

Some of the major observations from this project include:

* The dataset is highly imbalanced with respect to income, with most individuals earning USD 50,000 or less.
* Education level has a strong relationship with income.
* The dataset is heavily dominated by observations from the United States, indicating representation bias.
* Weekly working hours differ across income groups.
* Workclass distribution is highly uneven, with the Private workclass containing most observations.
* Statistical tests confirmed that education and income are significantly associated.

---

## Tools and Technologies

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* GitHub

---

## Statistical Methods

The following statistical methods were used during the analysis.

* Chi Square Test
* ANOVA
* Cramer's V

---

## Final Report

The complete project report can be viewed using the link below.

**Google Docs Report**

https://docs.google.com/document/d/1ZPfQYS5cizRMhlrsJ1-vbt-LWjlfJehxCE3CGG0QRjU/edit?usp=sharing

---

## References

Brian Christian. *The Alignment Problem: Machine Learning and Human Values.*

UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/2/adult

---

## Course

**DATA 6550**

Data Ethics

Middle Tennessee State University

Summer 2026
