<div align="center">

# Master's in Artificial Intelligence — Project Portfolio

**Udacity × Woolf University**

[![Projects](https://img.shields.io/badge/projects-12-blue?style=for-the-badge)](#)
[![Nanodegrees](https://img.shields.io/badge/nanodegrees-4-green?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/status-3%2F11%2B%20complete-orange?style=for-the-badge)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

</div>

---

## Program Overview

A fully accredited Master's Degree in AI through Udacity and Woolf University. This repository aggregates all completed project submissions across 4 nanodegrees (3 core + 1 elective), organized as git submodules.

```
udacity-masters-ai-projects/
├── 01-AIPND/                     Core #1: AI Programming with Python
│   ├── pcep-capstone-amazon-reviews/     Python + pandas data analysis
│   └── sentimentscope-imdb/              Transformer sentiment classification
├── 02-ML-PyTorch/                Core #2: ML with PyTorch
│   ├── finding-donors-charityml/         Supervised learning (AdaBoost)
│   ├── image-classifier-cifar10/         CNN image classification
│   └── identify-customer-segments/       PCA + K-Means clustering
├── 03-Data-Analyst/              Core #3: Data Analyst
│   ├── investigate-tmdb-movies/          Exploratory data analysis
│   ├── real-world-data-wrangling/        Data wrangling pipeline
│   └── communicate-data-findings/        Data visualization storytelling
├── 04-Statistics/                Elective: Statistics for Data Analysis
│   ├── describe-health-sleep-quality/    Descriptive statistics
│   ├── basketball-scoring-probabilities/ Bayes' Theorem + binomial
│   ├── analyze-ab-test-results/          Hypothesis testing + simulation
│   └── model-salary-regression/          Multiple linear regression
└── README.md
```

---

## Projects

### Core #1: AI Programming with Python ✅

| # | Project | Tech Stack | Highlights |
|---|---------|-----------|------------|
| 1 | [PCEP Capstone: Amazon Reviews](01-AIPND/pcep-capstone-amazon-reviews) | Python, pandas, matplotlib | 34K product reviews, sentiment distribution, temporal analysis |
| 2 | [SentimentScope IMDB](01-AIPND/sentimentscope-imdb) | PyTorch, Transformers, BERT | 91.8% accuracy, fine-tuned DistilBERT, 50K movie reviews |

### Core #2: ML with PyTorch ✅

| # | Project | Tech Stack | Highlights |
|---|---------|-----------|------------|
| 3 | [Finding Donors for CharityML](02-ML-PyTorch/finding-donors-charityml) | scikit-learn, AdaBoost | 86.8% accuracy, feature importance analysis, 45K census records |
| 4 | [CIFAR-10 Image Classifier](02-ML-PyTorch/image-classifier-cifar10) | PyTorch, CNN | Custom CNN architecture, data augmentation, 60K images |
| 5 | [Identify Customer Segments](02-ML-PyTorch/identify-customer-segments) | PCA, K-Means, scikit-learn | Dimensionality reduction, 891K population records |

### Core #3: Data Analyst ✅

| # | Project | Tech Stack | Highlights |
|---|---------|-----------|------------|
| 6 | [Investigate TMDb Movies](03-Data-Analyst/investigate-tmdb-movies) | pandas, matplotlib | 10,878 movies, genre trends, revenue drivers |
| 7 | [Real World Data Wrangling](03-Data-Analyst/real-world-data-wrangling) | pandas, NumPy | FBI NICS gun data + US Census, gather-assess-clean pipeline |
| 8 | [Communicate Data Findings](03-Data-Analyst/communicate-data-findings) | matplotlib, seaborn | Ford GoBike, exploratory + explanatory visualization |

### Elective: Statistics for Data Analysis 🔄

| # | Project | Tech Stack | Highlights |
|---|---------|-----------|------------|
| 9 | [Health & Sleep Quality](04-Statistics/describe-health-sleep-quality) | pandas, python-pptx | 373 records, measures of center/spread, outlier detection |
| 10 | [Basketball Scoring Probabilities](04-Statistics/basketball-scoring-probabilities) | Bayes' Theorem | 1,434 Steph Curry shots, binomial distribution, conditional probability |
| 11 | [Analyze A/B Test Results](04-Statistics/analyze-ab-test-results) | NumPy, pandas | 69,889 visitors, Monte Carlo simulation, p-value < 0.001 |
| 12 | [Model Salary Regression](04-Statistics/model-salary-regression) | statsmodels, OLS | R² = 0.9145, 7 significant features, confidence intervals |

---

## Technical Skills Demonstrated

| Category | Technologies |
|----------|-------------|
| **Languages** | Python 3 |
| **Data Analysis** | pandas, NumPy, scipy |
| **Visualization** | matplotlib, seaborn, plotly |
| **Machine Learning** | scikit-learn, PyTorch, Transformers |
| **Statistics** | statsmodels, hypothesis testing, Bayesian inference |
| **Techniques** | Linear/Logistic Regression, PCA, K-Means, CNN, A/B Testing, Monte Carlo Simulation |

## Quick Start

```bash
# Clone with all project submodules
git clone --recurse-submodules https://github.com/LeoLin990405/udacity-masters-ai-projects.git

# Update all submodules
git submodule update --remote --merge
```

## License

MIT — Individual projects may have their own licenses.
