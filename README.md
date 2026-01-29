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

5. **Jupyter Notebook or VS Code**
   - Jupyter: Built-in with `pip install jupyter`
   - VS Code: [Download](https://code.visualstudio.com/) + Python extension

---

## 💻 Installation and Setup

### 🚀 FASTEST: Google Colab (10 minutes)

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

### 💻 LOCAL: Windows Installation (15-20 minutes)

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

### 🍎 LOCAL: macOS/Linux Installation (15-20 minutes)

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
│   └── lunar_design_parameters.csv    # Generated design specs
│
├── outputs/
│   ├── lunar_power_analysis.png       # Power curve visualization
│   ├── lunar_eda_sanity_checks.png    # Data quality charts
│   ├── lunar_statistical_analysis.png # Test results visualization
│   ├── lunar_financial_analysis.png   # Revenue projections
│   ├── lunar_tech_summary.csv         # Summary statistics
│   ├── lunar_statistical_results.csv  # Test results
│   ├── lunar_business_metrics.csv     # Financial metrics
│   └── lunar_sensitivity_analysis.csv # Scenario analysis
│
├── docs/
│   ├── README.md                      # This file
│   ├── QUICKSTART.md                  # 5-minute quick start
│   ├── SETUP_GUIDE.md                 # Complete setup guide
│   ├── PROJECT_SUMMARY.md             # Skills & learning outcomes
│   └── INDEX.md                       # Navigation guide
│
├── requirements.txt                   # Python dependencies
├── .env.example                       # Environment variables template
├── .gitignore                         # Git ignore rules
└── LICENSE                            # MIT License
```

---

## 🏃 Quick Start Guide

**Choose your path:**

### Path A: Google Colab (FASTEST - 10 min)
```
1. Go to colab.research.google.com
2. Upload 4 .ipynb files
3. Upload ab_data.csv
4. Run all cells
5. Get results in 25 minutes!
```

### Path B: Local Computer (15-20 min)
```
1. Clone repository
2. Create virtual environment
3. Install requirements.txt
4. Download ab_data.csv
5. jupyter notebook
6. Run all notebooks
7. Get results in 25 minutes!
```

### Path C: Full Setup with Documentation
- Read QUICKSTART.md (5 min)
- Follow SETUP_GUIDE.md (15-20 min)
- Explore PROJECT_SUMMARY.md (10 min)

---

## 📚 Usage Guide

### Running the Analysis Pipeline

**Notebook Execution Order:**

1. **01_lunar_design.ipynb** (Start here!)
   - Load raw data
   - Perform power analysis
   - Determine sample size requirements
   - Output: Design parameters CSV

2. **02_lunar_eda_sanity.ipynb**
   - Exploratory data analysis
   - Data quality validation
   - Group balance checks
   - Output: Sanity check visualizations

3. **03_lunar_statistical_test.ipynb**
   - Implement two-sample z-test
   - Calculate p-values and confidence intervals
   - Visualize test results
   - Output: Statistical analysis PNG

4. **04_lunar_business_impact.ipynb**
   - Calculate revenue impact
   - Perform ROI analysis
   - Run sensitivity analysis (7 scenarios)
   - Output: Financial analysis + CSV exports

### Understanding the Output

**After running all notebooks, you'll have:**

✅ 4 Professional PNG visualizations (ready for presentations)  
✅ 6 CSV files with detailed metrics  
✅ Console output with key statistics  
✅ Complete analysis pipeline documentation  

### Modifying Parameters

To experiment with different scenarios:

1. Open any notebook
2. Find the "Parameters" section (typically top cells)
3. Change values (e.g., significance level, ROI assumptions)
4. Re-run the notebook
5. Compare new results with original analysis

---

## 💪 Skills You'll Learn

### Statistical Concepts (6 topics)

- ✅ **Power Analysis** - Determining sample size and detecting effect sizes
- ✅ **Hypothesis Testing** - Two-sample z-test for proportions
- ✅ **P-values & Confidence Intervals** - Interpreting statistical significance
- ✅ **Type I & Type II Errors** - Understanding false positives/negatives
- ✅ **Effect Size (Cohen's h)** - Measuring practical significance
- ✅ **Statistical vs Practical Significance** - Beyond p-values

### Data Analysis Skills (5 techniques)

- ✅ **Exploratory Data Analysis (EDA)** - Understanding data distributions
- ✅ **Data Validation & Sanity Checks** - Ensuring data quality
- ✅ **Summary Statistics** - Calculating aggregations and metrics
- ✅ **Group Comparisons** - Analyzing differences between groups
- ✅ **Outlier Detection** - Identifying anomalies in data

### Business Analysis Skills (5 applications)

- ✅ **Revenue Impact Calculation** - Quantifying business outcomes
- ✅ **ROI & Payback Period** - Financial return analysis
- ✅ **Sensitivity Analysis** - Testing what-if scenarios
- ✅ **Decision Making** - From data to actionable insights
- ✅ **Stakeholder Communication** - Presenting results clearly

### Technical Skills (4 tools)

- ✅ **Python Programming** - pandas, numpy, scipy for data science
- ✅ **Statistical Computing** - scipy.stats for hypothesis testing
- ✅ **Data Visualization** - matplotlib and seaborn for professional charts
- ✅ **Jupyter Notebooks** - Interactive development and documentation

---

## 💼 Portfolio Value

### For Job Interviews

**What interviewers will see:**

- ✅ Real-world Kaggle dataset (not toy data)
- ✅ Complete analysis pipeline (design → test → impact)
- ✅ 1,200+ lines of professional, well-documented code
- ✅ Impressive metrics (207% lift with p<0.0001!)
- ✅ Statistical rigor (power analysis, effect sizes)
- ✅ Business focus (ROI: 7,064%)

**Talking points:**
```
"I analyzed an A/B test that showed 207% conversion lift, 
representing ₹495 Crore annual revenue impact with a 7,064% 
first-year ROI. I validated the design with power analysis, 
confirmed data quality with sanity checks, performed 
hypothesis testing with z-tests, and calculated business impact."
```

### For GitHub Portfolio

- ✅ 4 polished, well-commented Jupyter notebooks
- ✅ 4 publication-ready visualizations (300 DPI PNG)
- ✅ Professional README with setup instructions
- ✅ Complete documentation (7 guide files)
- ✅ Clear project structure
- ✅ Reproducible analysis pipeline

### For LinkedIn

**Post ideas:**

1. **Results Highlight:**
   "Just completed comprehensive A/B testing analysis: 207% conversion lift, ₹495 Cr annual revenue impact, 99.99% statistical confidence. Check out my GitHub portfolio! 📊📈 #DataScience #Analytics"

2. **Skills Showcase:**
   "New project: A/B testing with Python - Power analysis, hypothesis testing, ROI calculation, sensitivity analysis. Real data, real insights! 🔬 #DataAnalytics #Python"

3. **Technical Deep Dive:**
   "Implemented two-sample z-test for A/B testing analysis using scipy.stats. Full pipeline: design → EDA → hypothesis testing → business impact. Complete with visualizations and documentation! 💻"

---

## ⏱️ Time Commitment

| Phase | Duration | Details |
|-------|----------|---------|
| **Read QUICKSTART.md** | 5 min | Choose your setup path |
| **Setup & Installation** | 10-15 min | First-time setup only |
| **Run All Notebooks** | 25 min | Fully automated analysis |
| **Review Outputs** | 10 min | Study results and charts |
| **Master the Code** | 2-3 hours | Understand every calculation |
| **Portfolio Setup** | 1-2 hours | GitHub + LinkedIn |
| **Interview Preparation** | 1-2 hours | Practice your pitch |
| **TOTAL** | **8-10 hours** | **Complete mastery** |

---

## 🐛 Troubleshooting

### Common Issues & Solutions

#### Issue: "No module named 'pandas'"
**Solution:**
```bash
pip install -r requirements.txt
```
If that fails, install individually:
```bash
pip install pandas numpy scipy matplotlib seaborn jupyter
```

#### Issue: "File not found: ab_data.csv"
**Solution:**
1. Download from: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing
2. Place in project folder (same level as notebooks)
3. Or update file path in notebook:
```python
df = pd.read_csv('path/to/ab_data.csv')
```

#### Issue: "Jupyter command not found"
**Solution:**
```bash
pip install jupyter
jupyter notebook
```

#### Issue: Virtual environment not activating
**Windows:**
```bash
.venv\Scripts\activate
```
**macOS/Linux:**
```bash
source .venv/bin/activate
```

#### Issue: "PermissionError" on macOS/Linux
**Solution:**
```bash
chmod +x .venv/bin/python
source .venv/bin/activate
```

#### Issue: Colab upload timeout
**Solution:**
- Use Kaggle API integration in Colab
- Or re-upload in smaller chunks
- Check internet connection

### Getting Help

1. **Check Documentation:**
   - See SETUP_GUIDE.md → Troubleshooting section
   - Review PROJECT_SUMMARY.md for concepts

2. **Review Notebook Comments:**
   - Each cell has explanatory comments
   - Read output messages carefully

3. **Test with Sample Data:**
   - Run notebooks with smaller dataset first
   - Verify each step works

4. **Check Environment:**
   - Verify Python version: `python --version`
   - Verify virtual environment active: `(.venv)` in terminal
   - List installed packages: `pip list`

---

## 📚 Additional Resources

### Official Documentation

- **Python:** https://docs.python.org/3/
- **pandas:** https://pandas.pydata.org/docs/
- **NumPy:** https://numpy.org/doc/
- **SciPy:** https://docs.scipy.org/
- **Jupyter:** https://jupyter.readthedocs.io/
- **Matplotlib:** https://matplotlib.org/stable/contents.html
- **Seaborn:** https://seaborn.pydata.org/

### Learning Resources

- **Statistics:**
  - Khan Academy: Probability and Statistics
  - StatQuest with Josh Starmer (YouTube)

- **A/B Testing:**
  - Udacity: A/B Testing Course
  - Growth.com: A/B Testing Handbook

- **Python for Data Science:**
  - Real Python: Python Tutorials
  - DataCamp: Python Courses

- **Business Analytics:**
  - Google Analytics Academy
  - HubSpot Academy: Marketing Analytics

### Related Datasets

- Kaggle Datasets: https://www.kaggle.com/datasets
- Lunar Tech A/B Testing: https://www.kaggle.com/datasets/andrsulloa/lunar-tech-case-study-ab-testing

---

## 🎉 Next Steps

### Immediate Actions

**Today (30 min):**
1. Read QUICKSTART.md
2. Choose setup path (Colab or Local)
3. Download ab_data.csv from Kaggle

**Tomorrow (1 hour):**
1. Complete setup
2. Run all 4 notebooks
3. Review outputs

### Deeper Learning

**Week 1 (3-4 hours):**
- Study each notebook's code
- Understand calculations
- Modify parameters and experiment

**Week 2 (2-3 hours):**
- Upload to GitHub
- Create portfolio README
- Update LinkedIn profile

**Month 1+:**
- Use in job interviews
- Reference in applications
- Build similar projects

### Taking It Further

- Extend analysis to multivariate testing
- Build interactive dashboard
- Create web app for test analysis
- Develop testing framework

---

## 🎓 Learning Outcomes

After completing this project, you can confidently say:

**"I can analyze A/B tests end-to-end, from experimental design to business impact."**

### You'll be able to:

**Explain:**
- How A/B tests work and when to use them
- Statistical significance vs practical significance
- Power analysis and sample size determination
- ROI calculation and business impact

**Demonstrate:**
- "I validated the test design with power analysis"
- "I confirmed data quality with sanity checks"
- "I performed hypothesis testing with z-tests"
- "I calculated business ROI with sensitivity analysis"

**Quantify:**
- "207% conversion lift (highly significant at p<0.0001)"
- "₹495 Crore annual revenue impact"
- "7,064% first-year ROI"
- "3-day payback period"

---

## 📞 Contact & Support

### Questions or Feedback?

- **GitHub Issues:** [Report Issues](https://github.com/your-username/lunar-tech-ab-testing/issues)
- **GitHub Discussions:** [Start Discussion](https://github.com/your-username/lunar-tech-ab-testing/discussions)
- **Email:** your-email@example.com
- **LinkedIn:** [Your Profile](https://linkedin.com/in/your-profile)

### Getting in Touch

Feel free to:
- Ask questions about the project
- Share improvements or modifications
- Report bugs or issues
- Suggest additional analysis

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use for personal/commercial projects
- ✅ Modify and distribute
- ✅ Use in your portfolio
- ✅ Reference in interviews

---

## 🙏 Acknowledgments

- **Kaggle** - For the Lunar Tech A/B Testing dataset
- **SciPy** - For statistical testing tools
- **Pandas & NumPy** - For data manipulation
- **Matplotlib & Seaborn** - For visualization capabilities
- **Python Community** - For the amazing ecosystem

---

## ✅ Quick Checklist

Before you start, verify:

- [ ] Python 3.8+ installed
- [ ] pip and Git available
- [ ] GitHub/Kaggle account (optional)
- [ ] Internet connection for downloads
- [ ] ~500MB free disk space
- [ ] 30 minutes available for setup

After setup:

- [ ] Virtual environment created & activated
- [ ] Dependencies installed successfully
- [ ] ab_data.csv in project folder
- [ ] Jupyter notebook running
- [ ] First notebook loads without errors

After running:

- [ ] 4 PNG visualizations created
- [ ] 6 CSV files exported
- [ ] Console shows p-value < 0.0001
- [ ] Results match expected output
- [ ] No error messages

---

## 🚀 Ready to Get Started?

1. **Read:** QUICKSTART.md (5 min)
2. **Setup:** Follow installation steps (10-20 min)
3. **Run:** Execute all notebooks (25 min)
4. **Analyze:** Study results (10 min)
5. **Master:** Understand the code (2-3 hours)
6. **Share:** Add to portfolio (1-2 hours)

```

---

**Last Updated:** January 27, 2026  
**Quality:** ⭐⭐⭐⭐⭐ Enterprise Grade

© 2026 Lunar Tech A/B Testing Project. All rights reserved.

