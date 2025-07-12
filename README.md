# Task 1 - Iris Dataset Visualization  
**DeveloperHub Corporation | AI/ML Engineering Internship**

## 🔍 Objective  
Explore and visualize the famous **Iris dataset** to understand its structure, feature relationships, distributions, and potential outliers.

---

## 📊 Key Concepts  
- Data loading and inspection using **pandas**
- Summary statistics using `.info()` and `.describe()`
- Basic plotting and visualization with **matplotlib** and **seaborn**
  - Scatter plots
  - Histograms
  - Box plots

---

## 🧪 Dataset  
The **Iris dataset** is a classical dataset in machine learning and statistics. It contains:

- **150 rows (samples)**
- **4 numeric features**:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
- **1 categorical label**:
  - `species` (setosa, versicolor, virginica)

Dataset is loaded using:
```python
import seaborn as sns
iris = sns.load_dataset("iris")
