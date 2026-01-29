# Lunar Tech A/B Testing Project

**A comprehensive end-to-end A/B testing analysis project demonstrating statistical rigor and business impact calculation for conversion rate optimization.**

Analyze real-world A/B test data using advanced statistical methods, create professional visualizations, and calculate business impact metrics. This project combines statistical hypothesis testing with practical business analysis to understand test results comprehensively.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Key Results](#key-results)
- [Project Deliverables](#project-deliverables)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Installation and Setup](#installation-and-setup)
- [Project Structure](#project-structure)
- [Quick Start Guide](#quick-start-guide)
- [Usage Guide](#usage-guide)
- [Skills You'll Learn](#skills-youll-learn)
- [Portfolio Value](#portfolio-value)
- [Troubleshooting](#troubleshooting)
- [Additional Resources](#additional-resources)
- [Contact](#contact)
- [License](#license)

---

## 🎯 Overview

This project demonstrates a complete A/B testing pipeline for **Lunar Tech**, an ed-tech platform conducting a conversion rate optimization experiment. The analysis covers:

- **Experimental Design**: Power analysis and sample size determination
- **Data Quality Validation**: Sanity checks and exploratory data analysis
- **Statistical Analysis**: Two-sample z-test for proportion hypothesis testing
- **Business Impact**: ROI calculation and sensitivity analysis

**Real Dataset:** Kaggle's Lunar Tech A/B Testing Case Study  
**Analysis Pipeline:** 4 interconnected Jupyter notebooks with 1,200+ lines of production-ready code  
**Output Quality:** Professional 300 DPI visualizations + 6 CSV data exports  

---

## 🎓 Key Results

### Statistical Analysis Summary

```
CONVERSION RATE ANALYSIS:
├─ Control Group CTR:        19.89%
├─ Experimental Group CTR:   61.16%
├─ Absolute Lift:            +41.27 percentage points
├─ Relative Lift:            +207% (HIGHLY SIGNIFICANT!)
├─ Z-Statistic:              -59.44
├─ P-Value:                  < 0.0001 (99.99% confidence)
├─ Effect Size (Cohen's h):  1.54 (EXTRAORDINARILY LARGE)
└─ Statistical Power:        99.99%
```

### Business Impact Analysis

```
FINANCIAL IMPACT:
├─ Annual Revenue Increase:  ₹495 Crore
├─ Year 1 ROI:               7,064% (70x return!)
├─ Payback Period:           3 days
├─ Additional Annual Enrolls: 3,062,400
├─ Monthly Revenue Boost:    ₹41.25 Crore
└─ 5-Year Revenue Impact:    ₹2,475 Crore
```
---

## 📦 Project Deliverables

### 4 Jupyter Notebooks

| Notebook | Focus Area | Lines | Runtime | Output |
|----------|-----------|-------|---------|--------|
| **01_lunar_design.ipynb** | Power analysis & experimental design | 310 | Power curve, design parameters |
| **02_lunar_eda_sanity.ipynb** | Data quality validation & EDA | 290  | Sanity check visualizations |
| **03_lunar_statistical_test.ipynb** | Hypothesis testing & z-test | 310  | Statistical analysis results |
| **04_lunar_business_impact.ipynb** | ROI & sensitivity analysis | 285 | Business metrics & projections |

### Output Files Generated

**Professional Visualizations (PNG, 300 DPI):**
- `lunar_power_analysis.png` - Power curves and design summary
- `lunar_eda_sanity_checks.png` - Data distribution and quality checks
- `lunar_statistical_analysis.png` - Hypothesis test results visualization
- `lunar_financial_analysis.png` - Revenue projections and ROI analysis

**Data Exports (CSV):**
- `lunar_design_parameters.csv` - Experimental design specifications
- `lunar_tech_data_raw.csv` - Raw dataset summary
- `lunar_tech_summary.csv` - Aggregated statistics
- `lunar_statistical_results.csv` - Test results and p-values
- `lunar_business_metrics.csv` - Financial impact calculations
- `lunar_sensitivity_analysis.csv` - What-if scenario results

---

## 🛠 Technology Stack

### Python Libraries & Versions

| Library | Version | Purpose |
|---------|---------|---------|
| **Python** | 3.8+ | Programming language |
| **Jupyter Notebook** | Latest | Interactive development environment |
| **pandas** | 1.5+ | Data manipulation and analysis |
| **numpy** | 1.24+ | Numerical computing |
| **scipy** | 1.10+ | Statistical testing (scipy.stats) |
| **matplotlib** | 3.6+ | Data visualization |
| **seaborn** | 0.12+ | Statistical visualization |
| **python-dotenv** | 1.0+ | Environment management |

### Development Environment

**Option A: Google Colab** (Recommended for beginners)
- Free cloud-based Jupyter environment
- Pre-installed libraries (most of them)
- No local setup required
- Works in any web browser

**Option B: Local Installation**
- Python 3.8+ installed
- Virtual environment (venv)
- All packages from requirements.txt
- Works offline

**Option C: Anaconda**
- Anaconda Distribution (includes Python + conda)
- Conda package manager for easy installation
- Pre-configured environments

---

## 📋 Prerequisites

Before starting, ensure you have:

1. **Python 3.8 or higher**
   - [Download Python](https://www.python.org/downloads/)
   - Verify: `python --version`

2. **pip (Python Package Manager)**
   - Usually comes with Python
   - Verify: `pip --version`

3. **Git** (optional, for cloning repository)
   - [Download Git](https://git-scm.com/downloads)
   - Verify: `git --version`

4. **Kaggle Dataset Access**
   - Dataset: [Lunar Tech Case Study A/B Testing](https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing)
   - Download: `ab_data.csv` (required to run notebooks)

5. **Jupyter Notebook or Antigravity**
   - Jupyter: Built-in with `pip install jupyter`
   - Antigravity: [Download](https://antigravity.google/) + Python extension

---

## 💻 Installation and Setup

### 🚀 FASTEST: Google Colab 

Perfect for first-time users - **zero setup required!**

**Step 1: Download files**
- Download all 4 .ipynb files from this repository
- Keep them in a folder on your computer

**Step 2: Open Google Colab**
```
Go to: https://colab.research.google.com
```

**Step 3: Upload notebooks**
- Click File → Upload notebook
- Select all 4 .ipynb files one by one
- Or click File → Open → Upload

**Step 4: Get Kaggle dataset**
- Visit: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing
- Click Download
- Extract `ab_data.csv`

**Step 5: Upload dataset to Colab**
- In first notebook cell, click file upload icon
- Upload `ab_data.csv`
- Or use this code in first cell:
```python
from google.colab import files
uploaded = files.upload()  # Select ab_data.csv
```

**Step 6: Install dependencies (run in first cell)**
```bash
!pip install -r requirements.txt
```

**Step 7: Run all notebooks**
- Execute cells in order: 01 → 02 → 03 → 04
- Watch results and visualizations appear!

---

### 💻 LOCAL: Windows Installation 

**Step 1: Clone repository**
```bash
git clone https://github.com/your-username/lunar-tech-ab-testing.git
cd lunar-tech-ab-testing
```

**Step 2: Create virtual environment**
```bash
python -m venv .venv
.venv\Scripts\activate
```
After activation, you'll see `(.venv)` in your terminal.

**Step 3: Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 4: Download Kaggle dataset**
- Visit: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing
- Download `ab_data.csv`
- Save to project folder: `lunar-tech-ab-testing/`

**Step 5: Launch Jupyter**
```bash
jupyter notebook
```
Browser opens automatically at `http://localhost:8888`

**Step 6: Open notebooks**
- Navigate to project folder
- Open `01_lunar_design.ipynb`
- Run cells in order!

---

### 🍎 LOCAL: macOS/Linux Installation 

**Step 1: Clone repository**
```bash
git clone https://github.com/your-username/lunar-tech-ab-testing.git
cd lunar-tech-ab-testing
```

**Step 2: Create virtual environment**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

**Step 3: Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 4: Download Kaggle dataset**
- Visit: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing
- Download `ab_data.csv`
- Save to project folder

**Step 5: Launch Jupyter**
```bash
jupyter notebook
```

**Step 6: Open and run notebooks**
- Open `01_lunar_design.ipynb`
- Execute cells in order (01 → 02 → 03 → 04)

---

## 📁 Project Structure

```
lunar-tech-ab-testing/
│
├── 01_lunar_design.ipynb              # Experimental design & power analysis
├── 02_lunar_eda_sanity.ipynb          # EDA & data validation
├── 03_lunar_statistical_test.ipynb    # Hypothesis testing & z-test
├── 04_lunar_business_impact.ipynb     # ROI & sensitivity analysis
│
├── data/
│   ├── ab_data.csv                    # Raw Kaggle dataset (download required)
│   ├── lunar_design_parameters.csv    # Generated design specs
│   │── lunar_tech_summary.csv         # Summary statistics
│   ├── lunar_statistical_results.csv  # Test results
│   ├── lunar_business_metrics.csv     # Financial metrics
│   └── lunar_sensitivity_analysis.csv # Scenario analysis
│
├── images/
│   ├── lunar_power_analysis.png       # Power curve visualization
│   ├── lunar_eda_sanity_checks.png    # Data quality charts
│   ├── lunar_statistical_analysis.png # Test results visualization
│   ├── lunar_financial_analysis.png   # Revenue projections
│   
├── requirements.txt                   # Python dependencies
├── .env.example                       # Environment variables template
├── .gitignore                         # Git ignore rules
└── LICENSE                            # MIT License
```

---

### Modifying Parameters

To experiment with different scenarios:

1. Open any notebook
2. Find the "Parameters" section (typically top cells)
3. Change values (e.g., significance level, ROI assumptions)
4. Re-run the notebook
5. Compare new results with original analysis

---

## 💪 Skills What've Learn

- ✅ **Power Analysis** - Determining sample size and detecting effect sizes
- ✅ **Hypothesis Testing** - Two-sample z-test for proportions
- ✅ **P-values & Confidence Intervals** - Interpreting statistical significance
- ✅ **Type I & Type II Errors** - Understanding false positives/negatives
- ✅ **Effect Size (Cohen's h)** - Measuring practical significance
- ✅ **Statistical vs Practical Significance** - Beyond p-values
- ✅ **Exploratory Data Analysis (EDA)** - Understanding data distributions
- ✅ **Data Validation & Sanity Checks** - Ensuring data quality
- ✅ **Summary Statistics** - Calculating aggregations and metrics
- ✅ **Group Comparisons** - Analyzing differences between groups
- ✅ **Outlier Detection** - Identifying anomalies in data
- ✅ **Revenue Impact Calculation** - Quantifying business outcomes
- ✅ **ROI & Payback Period** - Financial return analysis
- ✅ **Sensitivity Analysis** - Testing what-if scenarios
- ✅ **Decision Making** - From data to actionable insights
- ✅ **Stakeholder Communication** - Presenting results clearly
- ✅ **Python Programming** - pandas, numpy, scipy for data science
- ✅ **Statistical Computing** - scipy.stats for hypothesis testing
- ✅ **Data Visualization** - matplotlib and seaborn for professional charts
- ✅ **Jupyter Notebooks** - Interactive development and documentation

---

#### Issue: "File not found: ab_data.csv"
**Solution:**
1. Download from: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing
2. Place in project folder (same level as notebooks)
3. Or update file path in notebook:
```python
df = pd.read_csv('path/to/ab_data.csv')
```

## 📚 Additional Resources

### Official Documentation

- **Python:** https://docs.python.org/3/
- **pandas:** https://pandas.pydata.org/docs/
- **NumPy:** https://numpy.org/doc/
- **SciPy:** https://docs.scipy.org/
- **Jupyter:** https://jupyter.readthedocs.io/
- **Matplotlib:** https://matplotlib.org/stable/contents.html
- **Seaborn:** https://seaborn.pydata.org/

### Related Datasets

- Kaggle Datasets: https://www.kaggle.com/datasets
- Lunar Tech A/B Testing: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing

---

## 📞 Contact & Support

### Questions or Feedback?

- **GitHub Issues:** [Report Issues](https://github.com/your-username/lunar-tech-ab-testing/issues)
- **GitHub Discussions:** [Start Discussion](https://github.com/your-username/lunar-tech-ab-testing/discussions)
- **Email:** nitinlingwal91@gmail.com
- **LinkedIn:** [Your Profile](www.linkedin.com/in/nitinlingwal)

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use for personal/commercial projects
- ✅ Modify and distribute
- ✅ Use in your portfolio

---

## 🚀 Ready to Get Started?

1. **Read:** QUICKSTART.md (5 min)
2. **Setup:** Follow installation steps (10-20 min)
3. **Run:** Execute all notebooks (25 min)
4. **Analyze:** Study results (10 min)
5. **Master:** Understand the code (2-3 hours)
6. **Share:** Add to portfolio (1-2 hours)

```

**Last Updated:** January 27, 2026  
**Quality:** ⭐⭐⭐⭐⭐ Enterprise Grade

© 2026 Lunar Tech A/B Testing Project. All rights reserved.

