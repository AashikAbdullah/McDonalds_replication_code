# 🍔 McDonald's Customer Segmentation Using K-Means Clustering

This project performs **market segmentation analysis** on McDonald’s survey data using **K-Means clustering**. The goal is to identify meaningful customer segments based on attitudes toward McDonald's food (e.g., tasty, healthy, greasy) and understand their demographic profiles.

---

## 📁 Project Structure

- `McDonalds_Segmentation.ipynb`  
  → A clean Jupyter Notebook performing clustering and visualization using PCA and K-Means.

- `mcdonalds.csv`  
  → The dataset containing binary (Yes/No) responses on food perception, demographic variables (Age, Gender), and visit behavior.

- `README.md`  
  → Documentation to guide usage and understanding of the project.

---

## 📊 Dataset Overview

The dataset includes:

- **11 binary attitude variables**  
  (`tasty`, `fattening`, `healthy`, `greasy`, `cheap`, etc.)

- **Target sentiment**:  
  `Like` score from -3 to +4 indicating general sentiment.

- **Demographics and behavior**:  
  `Age`, `Gender`, `VisitFrequency`

Each row represents one respondent.

---

## 🔍 Analysis Steps

1. **Data Preprocessing**
   - Convert Yes/No answers into binary (1/0)
   - Select only relevant columns for clustering

2. **Dimensionality Reduction**
   - Use PCA to reduce dimensions for visual interpretation

3. **K-Means Clustering**
   - Group customers into clusters based on attitudes
   - Assign a cluster label to each respondent

4. **Cluster Profiling**
   - Use bar plots and tables to describe each segment
   - Compare cluster differences in demographics and sentiment

---

## 🛠 Technologies Used

- `Python`  
- `Pandas`, `NumPy` for data handling  
- `Seaborn`, `Matplotlib` for visualization  
- `Scikit-learn` for PCA and KMeans clustering

---

## 📈 Key Visuals Produced

- 2D scatterplot showing clusters using PCA
- Bar charts showing average scores across clusters
- Demographic summary per segment (age, gender, frequency)

---

## 💡 Insights Gained

- Different segments perceive McDonald’s differently (e.g., some find it convenient and cheap, others greasy or unhealthy).
- Age and visit frequency vary across clusters, useful for targeted marketing.
- Clustering reveals meaningful patterns not obvious through summary stats alone.

---

## ▶️ How to Run the Notebook

1. Clone or download the repo
2. Ensure you have Jupyter and necessary Python libraries installed
3. Open `McDonalds_Segmentation.ipynb`
4. Run all cells from top to bottom

---

## 📄 License

This project is licensed under the MIT License.

---

