# AI/ML Internship Tasks – GitHub Repository

## Task 1: Exploring and Visualizing a Simple Dataset

### Task Objective
Learn how to load, inspect, and visualize a dataset to understand data trends and distributions using Python data science libraries.

---

### Dataset Used
**Iris Dataset**
- **Source:** Seaborn built-in / UCI Machine Learning Repository
- **Format:** CSV-compatible (150 rows × 5 columns)
- **Features:** `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`
- **Classes:** 3 species — Setosa, Versicolor, Virginica (50 samples each)

---

### Models Applied
No predictive model is trained in this task.  
The focus is entirely on **Exploratory Data Analysis (EDA)** using:
- `pandas` – data loading and inspection
- `matplotlib` & `seaborn` – visualizations

---

### Key Results and Findings

| Finding | Detail |
|--------|--------|
| Dataset Shape | 150 rows × 5 columns |
| Missing Values | None – dataset is clean |
| Class Balance | Perfectly balanced (50 per species) |
| Best Discriminating Features | Petal length & petal width |
| Separability | Setosa is linearly separable; Versicolor & Virginica overlap |
| Strongest Correlation | Petal length ↔ Petal width (r ≈ 0.96) |
| Outliers | Minor outliers in sepal_width for Setosa |

#### Visualizations Produced:
- Scatter plots (sepal and petal features by species)
- Pair plot (all feature combinations)
- Histograms (value distributions per feature)
- Box plots (outlier detection per feature)
- Correlation heatmap

---

### Skills Demonstrated
- Data loading and inspection using pandas
- Descriptive statistics and data exploration
- Basic plotting and visualization with seaborn and matplotlib

---

### How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook Task1_Iris_EDA.ipynb
```

---

### Submission Requirements Checklist
- [x] Clear problem statement and goal
- [x] Dataset loading and preprocessing
- [x] Data visualization and exploration
- [x] Explanation of results and final insights
- [x] Code is clean, modular, and commented
- [x] README.md with task objective, dataset, models, and results
