# 2x2 Contingency Table Calculator

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:134E5E,100:71B280&height=220&section=header&text=2x2%20Contingency%20Table%20Calculator&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Master%20Biostatistics%20And%20Epidemiological%20Research&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-1.8.0-71B280?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-89.2K-134E5E?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20r%20%7C%20python-E91E63?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 📊 The Definitive Tool For Statistical Analysis

In the fields of medicine, biology, and social sciences, researchers constantly need to determine if there is a significant association between two categorical variables. Does a new drug reduce recovery time? Is there a link between a specific gene and a disease? The **2x2 Contingency Table Calculator** is a comprehensive, open-source statistical toolkit designed to answer these questions with precision.

This repository provides a complete suite of statistical tests for 2x2 tables. It goes far beyond a simple chi-square test. It includes calculations for **Odds Ratios (OR)**, **Relative Risk (RR)**, **Absolute Risk Reduction (ARR)**, and **Number Needed to Treat (NNT)**. It also includes exact tests like **Fisher's Exact Test** for small sample sizes, and calculates confidence intervals for all metrics.

Whether you are a medical student analyzing a clinical trial, a data scientist working on A/B testing, or a researcher publishing a paper, this tool ensures your statistical analysis is accurate, reproducible, and ready for peer review. It features a clean web interface, an R package, and a Python library, making it accessible to everyone.

<img width="300" height="231" alt="TwobyTwoIn" src="https://github.com/user-attachments/assets/c351d181-0e7f-4191-8653-d7100f2190ed" />


---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🧮 **Comprehensive Metrics** | Instantly calculate Odds Ratios, Relative Risk, and NNT |
| 📉 **Confidence Intervals** | 95% and 99% CIs for all effect size measures |
| 🧪 **Exact Tests** | Fisher's Exact Test and Barnard's Exact Test for small samples |
| 📊 **Yates Correction** | Automatic correction for continuity in Chi-Square tests |
| 🐍 **Python & R APIs** | Integrate the calculator directly into your data pipelines |
| 🖥️ **Interactive Web UI** | A beautiful interface to input data and visualize results |
| 📄 **Export to PDF** | Generate publication-ready tables and graphs |
| 📚 **Interpretation Guide** | Built-in explanations of what every p-value and metric means |

---

## 🔬 The Research Workflow

Instead of a standard installation guide, here is how this tool fits into your research process.

### Step 1: Data Entry
You have collected your data from a clinical trial. You have two groups: Treatment (Drug) and Control (Placebo). You have two outcomes: Recovered and Not Recovered. You enter these four numbers into the interactive web interface. The table instantly populates and validates the input.

### Step 2: Statistical Testing
The tool automatically runs a Chi-Square test with Yates correction. It also runs Fisher's Exact Test. It highlights the p-values in green if they are statistically significant (\(p < 0.05\)). You can toggle between one-tailed and two-tailed tests depending on your hypothesis.

### Step 3: Effect Size Calculation
P-values tell you *if* there is an effect, but not *how big* it is. The tool calculates the Odds Ratio and Relative Risk. It provides the 95% Confidence Interval for both. A result like "OR = 2.5 (95% CI: 1.2 - 4.8)" tells you the drug is significantly effective.

### Step 4: Publication Export
Once you are satisfied with the analysis, click "Export Report." The tool generates a beautifully formatted PDF containing the contingency table, the test results, and a forest plot of the effect sizes. This PDF is ready to be included in your manuscript.

---

<div align="center">

### 🔗 Ready to analyze your data?

[![Get Calculator](https://img.shields.io/badge/📊_GET_CALCULATOR-134E5E?style=for-the-badge&logoColor=white)](https://share.google/2m7kFst69wwSudyKl)

</div>

---

## 🧠 Under The Hood: Why Fisher's Exact Test Matters

The Chi-Square test is the most common test for 2x2 tables, but it relies on an approximation that assumes large sample sizes. When your sample size is small (typically when any cell in the table has an expected count of less than 5), the Chi-Square test becomes unreliable.

This is where **Fisher's Exact Test** comes in. Instead of relying on an approximation, Fisher's test calculates the exact probability of observing your data (and more extreme data) under the null hypothesis. It uses the hypergeometric distribution.

Our calculator automatically detects small sample sizes and prompts you to use Fisher's Exact Test. It computes the exact p-value using highly optimized algorithms, ensuring that your results are mathematically rigorous. This is critical for rare disease research or early-stage clinical trials where sample sizes are inherently small.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-71B280?style=for-the-badge&logoColor=black)](https://share.google/2m7kFst69wwSudyKl)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

Statistical software must be accurate and transparent. If you have found a bug, improved the confidence interval calculation, or want to add support for a new statistical test, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-test`).
3. **Commit** your changes (`git commit -m 'Add new test'`).
4. **Push** to the branch (`git push origin feature/new-test`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your research, ask for help with statistical interpretation, and discuss the latest trends in biostatistics.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@contingency-calc.dev.

---

<div align="center">

### ⭐ If this tool helps your research, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/2x2-contingency-table-calculator)

---

### 🚀 Start analyzing your data today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-E91E63?style=for-the-badge&logoColor=white)](https://share.google/2m7kFst69wwSudyKl)

<sub>Crafted with precision and ❤️ by the 2x2 Contingency Table community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:71B280,100:134E5E&height=120&section=footer)

</div>
