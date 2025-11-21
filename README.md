# 🚨 Cybersecurity Incident Temporal Clustering

This project performs **K-Means clustering** on cybersecurity incident timestamps to identify temporal patterns based on hour, day of week, and month.

---

## 📌 Features
- Extracts temporal features: `hour`, `day_of_week`, `month`
- Scales data using **StandardScaler**
- Applies **K-Means (3 clusters)** for grouping
- Visualizes clustering using a scatter plot
- Easy to customize and extend

---

## 📊 Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

---

## 📁 How to Run
1. Place your dataset file as `incidents.csv` in the project directory.
2. Run the Python script.
3. View the generated clustering visualization.

---

## 📂 Required Dataset Format
Your CSV must contain a `Timestamp` column. Example:
```csv
Timestamp
2024-05-21 14:23:10
2024-05-21 08:12:45
```

---

## 📸 Output
A scatter plot showing clusters based on:
- **Hour of the Day**
- **Day of the Week**

---

## 🧠 Purpose
This project helps analyze cybersecurity incident patterns to understand **when incidents occur most frequently**, supporting better monitoring and response strategies.
