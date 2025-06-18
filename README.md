# Google Play Store Data Analysis & Feature Engineering

This project covers comprehensive data preprocessing steps on the Google Play Store dataset. It includes:

- 🧹 Data Cleaning  
- 📊 Exploratory Data Analysis (EDA)  
- 🧠 Feature Engineering  

The goal is to understand the app market trends, clean inconsistent entries, and prepare the dataset for further Machine Learning use.

---

## 📁 Project Structure

📦google-playstore-data-cleaning-eda-feature-engg/
┣ 📄 README.md
┣ 📄 play_store_eda.ipynb
┣ 📂 data/ (optional: if raw data included)


---

## 📌 Dataset

The dataset is publicly available and contains app metadata scraped from the Google Play Store.  
Typical fields include: `App`, `Category`, `Rating`, `Reviews`, `Size`, `Installs`, `Type`, `Price`, `Genres`, `Content Rating`, etc.

---

## 🧹 Data Cleaning

Key cleaning tasks included:
- Replacing "Varies with device"
- Handling missing values (`NaN`)
- Cleaning `Size`, `Installs`, `Price` to convert them to numeric types
- Removing duplicates and erroneous entries

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed using:
- **Histograms** for distribution of Ratings, Sizes, Prices
- **Bar Charts** for app categories
- **Boxplots** for outlier detection
- **Correlation Heatmaps** for numerical features

### Some insights:
- Most apps are free
- Game and Tools categories dominate the store
- Ratings are heavily right-skewed
- Size does not significantly correlate with Ratings

---

## 🧠 Feature Engineering

New features created:
- `Size_MB` from original `Size` column
- `Installs_cleaned` as numeric
- Normalized/encoded fields for ML-readiness

Future direction: You can use this cleaned and engineered data for classification or regression (e.g., predicting app rating or price).

---

## 🛠️ Tools Used

| Tool         | Purpose               |
|--------------|------------------------|
| `Pandas`     | Data manipulation      |
| `NumPy`      | Numerical operations   |
| `Matplotlib` | Data visualization     |
| `Seaborn`    | Statistical plots      |
| `Jupyter`    | Interactive notebooks  |

---

## 📈 Future Work

- Apply ML models for app success prediction
- Deploy a dashboard for dynamic visualization
- Add NLP on app descriptions

---

## 🔗 Author

**Yash Modi**  
Feel free to connect or fork the repo!


