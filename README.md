<div align="center">

# 🎨 Seaborn — Statistical Data Visualization

**Beautiful, insight-driven charts in a few lines of code — 9 hands-on Jupyter lessons on relational, categorical, distribution and matrix plots with Seaborn.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-4C72B0)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Backend-11557C)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)
![Level](https://img.shields.io/badge/Level-Beginner%20→%20Intermediate-0EA5A4)

</div>

---

## 🎯 What you'll learn

Seaborn is where visualization meets **exploratory data analysis**. Every lesson starts with *when* a plot is the right choice, then layers on Seaborn's semantic parameters (`hue`, `style`, `size`, `split`, `kind`) so you can compare groups and spot patterns at a glance.

Plots are organised the way you'll use them in real EDA:

- **Relational** — how two numerical variables move together
- **Categorical** — scatter, distribution and estimate plots across groups
- **Matrix** — heatmaps and cluster maps
- **Multi-plot grids** — joint plots and pair plots
- **Distributions** — histograms, KDE, rug and ECDF

---

## 📚 Lessons

| # | Lesson | What you'll learn | Dataset |
|---|---|---|---|
| 1 | [Scatter plots](1.%20SCATTER%20PLOTS.ipynb) | `relplot()` & `scatterplot()` with semantic parameters — `hue`, `style`, `size` | `tips` |
| 2 | [Strip & swarm plots](2.%20%281%29Categorical%20Scatterplots%20_%20Stripplots%20and%20Swarmplots.ipynb) | Categorical scatterplots, the jitter concept and `catplot()` | `tips` |
| 3 | [Box plots](3.%20%282%29BOX%20PLOT.ipynb) | Univariate and bivariate box plots, reading quartiles and outliers, link to the PDF | `tips` |
| 4 | [Violin plots](4.%282%29%20categorical%20distribution%20plots%28%28b.%20violin%20PLOTS%29.ipynb) | Box plot + KDE in one — `hue` and `split` for compact comparisons | `tips` |
| 5 | [Bar, count & point plots](5.%20%283%29categorical%20estimate%20plots.ipynb) | Categorical estimates — mean, median, sum and std with `estimator` | `tips` |
| 6 | [Heatmaps & cluster maps](6.%20%284%29%20categorical%20categorical%20plots%20%28a.%20Heatmaps%20b.%20clustermaps%29.ipynb) | Annotated heatmaps, colour maps, correlation-based clustering and z-scores | `flights` |
| 7 | [Joint plots](7.%20plotting%20sise%20by%20side%20graph%20using%20facetgrid%20%28a.%20JOINT%20PLOT%20%29.ipynb) | Scatter, hex, KDE and regression joint plots of two variables | `tips` |
| 8 | [Pair plots](8.%20PAIR%20PLOTS.ipynb) | Every pairwise relationship in a dataset at once — choosing the best features | `iris` |
| 9 | [Distribution plots](9.%20Distplots.ipynb) | Histograms, KDE, rug and ECDF with `displot`, `histplot`, `kdeplot` — survival by age | `titanic` |

---

## 🚀 Getting started

```bash
git clone https://github.com/ahmadhassan-aiops/seaborn.git
cd seaborn
pip install seaborn matplotlib pandas numpy jupyter
jupyter notebook
```

No downloads needed — every lesson uses Seaborn's built-in datasets (`tips`, `flights`, `iris`, `titanic`) loaded with `sns.load_dataset()`, so it works the same locally and on Google Colab.

> 💡 Lesson 9 also shows `distplot()`, which is deprecated in recent Seaborn versions. The modern replacements — `displot()`, `histplot()` and `kdeplot()` — are covered in the same notebook.

---

## 🧭 Part of a complete Data Science path

**Python basics → NumPy → Pandas → Matplotlib → Seaborn → Statistics → Machine Learning**

- 🐍 [Python for Data Science](https://github.com/ahmadhassan-aiops/python-for-data-science)
- 🔢 [NumPy](https://github.com/ahmadhassan-aiops/Numpy)
- 🐼 [Pandas](https://github.com/ahmadhassan-aiops/Pandas)
- 📈 [Matplotlib](https://github.com/ahmadhassan-aiops/matplotlib)
- 🎨 **Seaborn** ← you are here

---

## 👨‍🏫 About the author

**Ahmad Hassan** — AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you learn, please star the repo — it helps other students find it!
