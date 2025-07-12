
# ✅ Task 1: Dataset Exploration & Visualization (Iris)

## 🔹 Objective:
Explore the Iris flower dataset to understand its structure, visualize feature relationships, and identify patterns using basic statistical tools and charts.

## 📊 Dataset:
- **Source**: Built-in `Iris` dataset from `seaborn`
- **Attributes**:
  - `sepal_length`, `sepal_width`, `petal_length`, `petal_width`, `species`

## 🧠 Model Applied:
- No machine learning model applied; this task focuses on data exploration only

## ⚙️ Workflow:
1. Loaded dataset using `seaborn.load_dataset("iris")`
2. Displayed dataset shape, columns, types, and summary statistics
3. Plotted:
   - Pair plots to visualize relationships between features
   - Histograms for individual feature distributions
   - Box plots to spot outliers

## 📌 Key Findings:
- Clear visual separation between flower species based on petal measurements
- Setosa is the most easily separable species
- Petal length and petal width are strong indicators for classification

## 📦 Dependencies:
```bash
pip install pandas seaborn matplotlib
