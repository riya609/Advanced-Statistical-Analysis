# 📊 Advanced Statistical Analysis & Hypothesis Testing

### A Python-Based Statistical Research Project Using the Palmer Penguins Dataset

An end-to-end statistical analysis project demonstrating hypothesis testing, assumption checking, effect-size estimation, confidence intervals, and statistical inference using Python.

---

## 📌 Project Overview

This project explores statistical methods through the Palmer Penguins dataset. It combines exploratory data analysis with a range of parametric and non-parametric tests to demonstrate how statistical hypotheses can be evaluated using real-world biological measurements.

The project is implemented in a Jupyter Notebook, with an accompanying HTML report containing saved outputs and visualizations.

**Project goals:**
- Explore and compare statistical testing methods.
- Evaluate distributional assumptions before interpreting test results.
- Quantify effect sizes and uncertainty, not just statistical significance.
- Demonstrate reproducible analysis using Python.

## ✨ Key Features

### 1. Normality Testing
- Shapiro–Wilk test
- Kolmogorov–Smirnov test with Lilliefors correction

### 2. Hypothesis Testing
- Student's and Welch's t-tests
- Mann–Whitney U test
- One-way and two-way ANOVA
- Welch ANOVA
- Tukey HSD post-hoc comparisons
- Kruskal–Wallis test

### 3. Statistical Inference
- Effect-size calculations
- Bootstrap and permutation confidence intervals
- Statistical power analysis
- Holm correction for multiple comparisons
- Null and alternative hypothesis summaries

### 4. Reproducibility
- Fixed random seed: `42`
- Notebook-based analysis workflow
- Saved HTML report for reviewing outputs
- Dataset stored locally in CSV format

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Jupyter Notebook | Interactive analysis |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| SciPy | Statistical hypothesis tests |
| Statsmodels | Statistical modelling and inference |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualizations |

Install the dependencies listed in `requirements.txt`.

## 📂 Project Structure

```text
stats-project/
├── data/
│   └── penguins.csv
├── Advanced_Statistical_Analysis.ipynb
├── Advanced_Statistical_Analysis.html
├── README.md
└── requirements.txt
```

## 📊 Dataset

**Dataset:** Palmer Penguins

The dataset contains penguin observations and measurements, including species, island, bill dimensions, flipper length, body mass, and sex.

The project uses the local file `data/penguins.csv`.

**Original research reference:**

Gorman, K. B., Williams, T. D., & Fraser, W. R. (2014). *Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (genus Pygoscelis).* PLOS ONE, 9(3), e90081.

https://doi.org/10.1371/journal.pone.0090081

## 🚀 Getting Started

### Prerequisites
- Python installed
- Visual Studio Code
- Python and Jupyter extensions in VS Code

### Step 1: Open the project

Open the `stats-project` folder in VS Code.

### Step 2: Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

If PowerShell blocks activation, you can use the environment's Python executable directly:

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

### Step 3: Install dependencies

With the virtual environment activated:

```bash
python -m pip install -r requirements.txt
```

### Step 4: Launch the notebook

```bash
jupyter notebook Advanced_Statistical_Analysis.ipynb
```

Alternatively, open the `.ipynb` file directly in VS Code, select the `.venv` Python kernel, and choose **Run All**.

## 📈 How to Interpret Results

- **P-values:** Evaluate evidence against the null hypothesis in the context of the chosen test and its assumptions.
- **Confidence intervals:** Describe uncertainty around an estimated quantity.
- **Effect sizes:** Help assess the magnitude of a difference or association.
- **Multiple-testing correction:** Helps control false-positive risk when conducting multiple comparisons.
- **Statistical power:** Describes the probability of detecting an effect of a specified size under stated assumptions.

Statistical significance alone does not establish practical importance or causation. Test selection should account for the data structure, assumptions, and research question.

## 🔬 Reproducibility

The analysis uses a fixed random seed of `42` where applicable. To reproduce the analysis, use the provided CSV file, install the listed dependencies, select the appropriate Python environment, and execute the notebook cells in order.

Results may vary across library versions or environments. Record software versions when exact reproducibility is required.

## ⚠️ Limitations

- Findings depend on the available dataset and the selected statistical methods.
- Test assumptions must be checked before drawing conclusions.
- Multiple comparisons require careful interpretation.
- The project is an educational statistical analysis workflow; it does not automatically establish causal relationships.
- Reported conclusions should be interpreted alongside effect sizes, confidence intervals, assumptions, and study context.

## 🔮 Future Improvements

- Add automated tests for data validation and statistical functions.
- Include a more systematic comparison of test assumptions and selection criteria.
- Improve visual summaries and reporting of statistical results.
- Add a reproducible environment specification and automated analysis workflow.

## 👩‍💻 Author

**Riya Maheshwari**  
B.Tech — Computer Science and Engineering (Data Science)

GitHub: [riya609](https://github.com/riya609)

---

*Built as a learning and research project to strengthen practical skills in Python, statistical inference, and reproducible data analysis.*
