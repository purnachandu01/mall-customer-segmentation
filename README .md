
# 📊 Mall Customer Segmentation using K-Means Clustering

## 🧠 Objective
This project performs **unsupervised learning** using the **K-Means clustering algorithm** to segment customers based on their **Annual Income** and **Spending Score**. The goal is to identify distinct customer groups for better marketing and business strategies.

---

## 🗂️ Dataset

The dataset used is **Mall_Customers.csv**, which contains the following features:

- `CustomerID`: Unique identifier for each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income in thousand dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

---

## 📌 Tools & Libraries Used

- Python 3.x
- [Pandas](https://pandas.pydata.org/) – for data handling
- [Matplotlib](https://matplotlib.org/) – for data visualization
- [Scikit-learn](https://scikit-learn.org/) – for machine learning (K-Means)
- [Jupyter Notebook](https://jupyter.org/) – for interactive coding and documentation

---

## 📈 Methodology

1. **Data Loading**  
   Load the dataset and inspect the structure.

2. **Feature Selection**  
   Select `Annual Income` and `Spending Score` for clustering.

3. **Data Scaling**  
   Standardize the features using `StandardScaler`.

4. **Elbow Method**  
   Determine the optimal number of clusters by plotting Within-Cluster Sum of Squares (WCSS).

5. **Model Training**  
   Apply K-Means clustering using the optimal `k`.

6. **Visualization**  
   Plot clusters and centroids to visualize the customer segments.

---

## 📊 Results

- Used the **Elbow Method** to determine `k = 5` as the optimal number of clusters.
- Successfully visualized the 5 distinct customer groups.
- Provided valuable insights for customer-based marketing strategies.

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `mall customer segmentation.ipynb` and run all cells.

---

## 📎 File Structure

```
📁 mall-customer-segmentation/
├── mall customer segmentation.ipynb
├── Mall_Customers.csv
├── requirements.txt
└── README.md
```

---

## 🔍 Insights

- High income and high spending customers form a premium segment.
- Low income but high spending users may be targeted with offers.
- Low spending users across income brackets may require different marketing approaches.

---

## 📬 Contact

**Author:** Maxxy  
📧 Email: your-email@example.com  
🌐 GitHub: [github.com/your-username](https://github.com/your-username)
