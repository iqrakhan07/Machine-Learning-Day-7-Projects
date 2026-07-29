# Machine Learning Day 7 Projects  
## K-Means Clustering | Unsupervised Learning

This repository contains my **Machine Learning Day 7 projects** completed during my internship, focusing on **Unsupervised Machine Learning** using the **K-Means Clustering Algorithm**.

K-Means is a clustering algorithm that discovers hidden patterns in unlabeled data by grouping similar data points into meaningful clusters.

---

# 📌 Projects Included

## 1️⃣ Customer Segmentation using K-Means Clustering

### 📖 Project Overview

Customer Segmentation is a clustering-based approach used to divide customers into different groups based on their characteristics.

In this project, customers are grouped based on:

- Annual Income
- Spending Score

This helps businesses understand customer behavior and create better marketing strategies.

---

## ⚙️ How the Project Works

1. Load the customer dataset.
2. Select important features:
   - Annual Income (k$)
   - Spending Score (1-100)
3. Standardize the data using `StandardScaler`.
4. Apply the **Elbow Method** to find the optimal number of clusters.
5. Train the K-Means model with the selected value of K.
6. Assign customers into different clusters.
7. Calculate cluster centroids.
8. Visualize customer groups using scatter plots.

---

## 📊 Output

- Elbow Method Graph
- Customer Cluster Visualization
- Cluster Centroids
- Final Dataset with Cluster Labels

---

# 2️⃣ Movie Recommendation using K-Means Clustering

### 📖 Project Overview

This project uses K-Means Clustering to group users based on their movie genre preferences.

The system identifies users with similar interests and recommends movies based on their cluster group.

Features used:

- Action
- Comedy
- Drama
- Horror
- Romance
- Sci-Fi

---

## ⚙️ How the Project Works

1. Load the movie preference dataset.
2. Select movie genre rating features.
3. Standardize feature values using `StandardScaler`.
4. Apply the **Elbow Method** to determine the optimal number of clusters.
5. Train the K-Means clustering model.
6. Assign users into different clusters.
7. Analyze cluster preferences.
8. Identify similar users from the same cluster.

---

## 📊 Output

- Elbow Method Graph
- User Cluster Visualization
- Cluster Preference Analysis
- Similar User Recommendation

---

# 🔄 Machine Learning Workflow

```
              Dataset
                  │
                  ▼
          Feature Selection
                  │
                  ▼
          Data Standardization
                  │
                  ▼
           Elbow Method
        (Find Optimal K Value)
                  │
                  ▼
          K-Means Algorithm
                  │
                  ▼
          Generate Clusters
                  │
                  ▼
        Analyze Cluster Patterns
                  │
                  ▼
        Visualize Results
```

---

# 🧠 Concepts Learned

✔ Unsupervised Learning  
✔ K-Means Clustering Algorithm  
✔ Cluster Formation  
✔ Centroids  
✔ Feature Scaling  
✔ StandardScaler  
✔ Elbow Method  
✔ Data Visualization  
✔ Customer Segmentation  
✔ Recommendation Systems  

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 📂 Repository Structure

```
Machine-Learning-Day-7-Projects
│
├── Customer_Segmentation_KMeans.py
├── mall_customers.csv
│
├── Movie_Recommendation_KMeans.py
├── movies.csv
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

# 📈 Project Results

## Customer Segmentation

The model successfully grouped customers into different segments based on their income and spending behavior.

These clusters can help businesses:

- Identify high-value customers
- Understand customer patterns
- Improve marketing decisions

---

## Movie Recommendation

The model grouped users based on their movie preferences.

The clusters help identify:

- Users with similar interests
- Common genre preferences
- Potential movie recommendations

---

# 📦 Installation & Usage

### Clone the Repository

```bash
git clone https://github.com/iqrakhan07/Machine-Learning-Day-7-Projects.git
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run Projects

Customer Segmentation:

```bash
python Customer_Segmentation_KMeans.py
```

Movie Recommendation:

```bash
python Movie_Recommendation_KMeans.py
```

---

# 📚 Learning Outcome

Through these projects, I learned how unsupervised learning algorithms can discover hidden patterns from data without predefined labels.

I gained practical experience in:

- Implementing K-Means Clustering
- Selecting optimal clusters using the Elbow Method
- Performing feature scaling
- Visualizing clustering results
- Applying machine learning concepts to real-world problems

---

# ⭐ Acknowledgement

This project was completed as part of my **Machine Learning Internship Learning Journey at Visual Labs**.

---

⭐ If you find this repository useful, feel free to star it!
