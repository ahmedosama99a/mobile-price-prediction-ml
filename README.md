# 📱 Mobile Price Range Prediction

## 📌 Overview
This project aims to predict the price range of mobile phones using their specifications such as RAM, battery power, camera features, and more. We apply multiple machine learning models, evaluate their performance, and visualize decision boundaries.

---

## 🧠 Business Question
Can we accurately classify mobile phones into one of four price categories based on their features?

---

## 🧪 Dataset
- **Source**: train.csv
- **Target**: `price_range` (0 = very low, 1 = low, 2 = high, 3 = very high)
- **Features**: RAM, battery_power, px_height, sc_w, fc, etc.

---

## 🔄 Data Preprocessing
- Fixed zero values in `px_height`, `sc_w` by replacing them with median
- Applied outlier capping on `px_height` and `fc`
- Saved cleaned dataset to `cleaned_mobile_data.csv`
- Standardized features using `StandardScaler`

---

## 📊 Exploratory Data Analysis
- Visualized distributions and outliers using boxplots and histograms
- Correlation heatmap
- Scatterplots of key features vs. target
- Pie chart for class balance

---

## 🤖 Models Used
| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | ✅ Good |
| K-Nearest Neighbors (KNN) | ✅ Good |
| Decision Tree       | ✅ Good |

- Confusion matrices were plotted for each.
- Decision boundaries visualized for RAM vs. Battery.

---

## 📈 Visualizations
- Heatmaps for correlations
- Boxplots for outliers
- Decision boundaries using 2 features (RAM & Battery)

---

## 🧰 Tools Used
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

👤 Author
Ahmed Osama
📊 Data Science & AI Enthusiast