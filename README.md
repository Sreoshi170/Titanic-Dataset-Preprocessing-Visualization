

## 🚢 Titanic Dataset Preprocessing & Visualization

This project focuses on preprocessing and visualizing the famous Titanic dataset using Python. It aims to clean, transform, and prepare the data for future machine learning tasks, ensuring data quality and exploring patterns that might influence survival outcomes.

### 📌 Key Features:

* 📥 **Data Loading & Inspection:**

  * Loaded dataset using `pandas`.
  * Performed initial exploration using `.head()`, `.info()`, and `.shape()`.

* 🔍 **Missing Value Handling:**

  * Used **KNNImputer** from `sklearn` to fill missing values in numeric columns like `Age`.
  * Checked missing values pre- and post-imputation.

* 🔢 **Feature Engineering:**

  * Converted categorical variables (e.g., `Sex`) into numerical using `LabelEncoder`.
  * Standardized numerical features like `Age` using `StandardScaler`.

* 📊 **Data Visualization:**

  * Used **Seaborn** and **Matplotlib** to visualize data distributions.
  * Created **box plots** to detect and handle outliers.
  * Calculated interquartile range (IQR) and applied **whisker logic** to cap outliers in columns like `Age`, `Fare`, `SibSp`, etc.

* 🧹 **Outlier Treatment:**

  * Defined a custom function to calculate whiskers and capped values outside IQR to reduce the effect of extreme outliers.

---

### 🧰 Technologies Used:

* Python
* Pandas, NumPy
* Seaborn, Matplotlib
* Scikit-learn (KNNImputer, LabelEncoder, StandardScaler)

---

### 📁 Notebook Link:

This project was developed in Google Colab. You can find the notebook [here](https://colab.research.google.com/drive/1e5TFViy9J0_8oq0LiVFxnxNUKJYei3-0?usp=sharing).

---

### 📈 Next Steps:

This preprocessed data can now be used for:

* Classification modeling (e.g., predicting survival)
* Feature selection and engineering
* Further EDA and correlation analysis

---

### ✅ Outcome:

A well-cleaned and visualized Titanic dataset, ready for use in predictive modeling or deeper statistical analysis.
